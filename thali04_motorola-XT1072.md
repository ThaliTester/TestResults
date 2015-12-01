#### Test 52320939cae1769_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,D/AndroidRuntime( 4891): 
D/AndroidRuntime( 4891): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4891): CheckJNI is OFF
D/AndroidRuntime( 4891): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4910 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 4891): Shutting down VM
I/art     (  322): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 21.974ms
V/ActivityManager(  880): Display changed displayId=0
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 20.206ms
W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 22.707ms
,I/WebViewFactory( 4910): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4910): Time to load native libraries: 1 ms (timestamps 8454-8455)
I/LibraryLoader( 4910): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4910): Binding Chromium to main looper Looper (main, tid 1) {202359f}
,I/LibraryLoader( 4910): Expected native library version number "",actual native library version number ""
I/chromium( 4910): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4910): Initializing chromium process, singleProcess=true
W/art     ( 4910): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4910): ApplicationContext is null in ApplicationStatus
,W/chromium( 4910): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4910): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4910): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4910): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4910): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4910): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4910): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4910): Local Branch: 
I/Adreno-EGL( 4910): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4910): Local Patches: NONE
I/Adreno-EGL( 4910): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{139e6e44 u0 com.test.thalitest/.MainActivity t3}
,I/art     (  880): Explicit concurrent mark sweep GC freed 17866(939KB) AllocSpace objects, 2(192KB) LOS objects, 33% free, 19MB/29MB, paused 1.745ms total 116.397ms
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2803486b:true
,D/BluetoothAdapter( 4910): 520485910: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 4910): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4910): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4910): CordovaWebView is running on device made by: motorola
,W/art     ( 4910): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4910): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4910): Render dirty regions requested: true
,D/Atlas   ( 4910): Validating map...
,W/chromium( 4910): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4910): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4910): Enabling debug mode 0
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1093
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +987ms (total +1s93ms)
,W/IInputConnectionWrapper( 4910): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 4910): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4910): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4910): Cannot call determinedVisibility() - never saw a connection for the pid: 4910
,D/JsMessageQueue( 4910): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4910): JniHelper::setJavaVM(0xb7d48310), pthread_self() = -1207083504
D/JX-Cordova( 4910): jxcore cordova android initializing
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
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
,W/jxcore-log( 4910): Initializing JXcore engine
W/jxcore-log( 4910): JXcore engine is ready
,W/jxcore-log( 4910): Starting JXcore engine
,W/.test.thalitest( 4910): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10338 path="socket:[9321]" dev="sockfs" ino=9321 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 4910): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10338 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 4910): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10338 path="socket:[6549]" dev="sockfs" ino=6549 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 4910): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10338 path="socket:[21568]" dev="sockfs" ino=21568 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4910): Platform android
W/jxcore-log( 4910): 
W/jxcore-log( 4910): Process ARCH arm
W/jxcore-log( 4910): 
,E/global frequency( 2572): no tags to log
D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1452): Explicit concurrent mark sweep GC freed 53419(2MB) AllocSpace objects, 33(1038KB) LOS objects, 39% free, 7MB/12MB, paused 2.547ms total 61.861ms
,I/art     ( 2572): Explicit concurrent mark sweep GC freed 18974(1193KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/18MB, paused 1.114ms total 75.328ms
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     ( 1452): Explicit concurrent mark sweep GC freed 3848(161KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 510us total 27.096ms
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1539): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2572): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2572): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2572): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2572): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/jxcore-log( 4910): JXcore Cordova bridge is ready!
I/jxcore-log( 4910): 
,W/jxcore-log( 4910): JXcore engine is started
I/chromium( 4910): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/global frequency( 2572): BcsDSCheckin.events found events 71
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/jxcore-log( 4910): Toggling radios to true
I/jxcore-log( 4910): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  880): Message: 1
D/BluetoothManagerService(  880): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1452): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=4910, uid=10338
,E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,E/WifiStateMachine(  880): setting operational mode to 1
,I/jxcore-log( 4910): Radios toggled
I/jxcore-log( 4910): 
I/BSUtils ( 2572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ActivityManager(  880): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=4975 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/Settings( 1452): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
W/Settings( 1452): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1452): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,W/ResourcesManager( 4975): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/Checkin ( 2983): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2983): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/art     (  880): Explicit concurrent mark sweep GC freed 6989(369KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 2.152ms total 138.280ms
,D/AdapterServiceConfig( 4975): Adding HeadsetService
D/AdapterServiceConfig( 4975): Adding A2dpService
,D/AdapterServiceConfig( 4975): Adding HidService
D/AdapterServiceConfig( 4975): Adding HealthService
D/AdapterServiceConfig( 4975): Adding PanService
D/AdapterServiceConfig( 4975): Adding GattService
D/AdapterServiceConfig( 4975): Adding BluetoothMapService
,D/MMApiWebService( 2572): doRequest(): polling manager says we're not connected, returning with an error: 
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37c4de3c:true
,I/MMApiWebService( 2572): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/BluetoothAdapterState( 4975): make
,D/CCE     ( 2572): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2572): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2572): unknown error code mapping for: 0
,I/global frequency( 2572): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
I/BluetoothAdapterState( 4975): Entering OffState
I/bluedroid( 4975): init
,I/global frequency( 2572): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,I/bte_conf( 4975): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,D/Checkin ( 2572): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/bte_conf( 4975): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 4975): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 4975): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 4975): get_profile_interface socket
I/bluedroid( 4975): get_profile_interface map_client
,I/GKI_LINUX( 4975): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 4975): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): Bluetooth Adapter name changed to XT1072
D/BluetoothAdapterProperties( 4975): Name is: XT1072
D/BluetoothManagerService(  880): Stored Bluetooth name: XT1072
,D/BluetoothManagerService(  880): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  880): Message: 40
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 4975): config_hci_snoop_log
D/BluetoothManagerService(  880): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  880): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterState( 4975): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 4975): Setting state to 11
I/BluetoothAdapterState( 4975): Bluetooth adapter state changed: 10-> 11
D/BluetoothBondStateMachine( 4975): make
D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  880): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 4975): StableState(): Entering Off State
,D/TCMD    (  441): NL - Read 1008 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
,D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 1008 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
,D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/QsoftapCmd(  299): Got softap fwreload command we are passing on
,D/SoftapController(  299): Softap fwReload - Ok
,D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring down wlan0
D/CommandListener(  299): Clearing all IP addresses on wlan0
,I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5014 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
E/WifiStateMachine(  880): setWifiState: enabling
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  880): InitialState.processMessage what=4
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  880): Supplicant start successful
D/WifiMonitor(  880): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/BluetoothAdapterState( 4975): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,D/BluetoothHeadset(  880): Proxy object connected
D/BluetoothHeadset( 1504): Proxy object connected
,D/HeadsetService( 4975): Received start request. Starting profile...
D/BluetoothHeadset( 1539): Proxy object connected
I/BluetoothHeadsetServiceJni( 4975): classInitNative: succeeds
,D/HeadsetStateMachine( 4975): make
,D/BluetoothHeadset( 1504): Proxy object connected
,I/wpa_supplicant( 5020): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5020): Long line in configuration file truncated
I/wpa_supplicant( 5020): rfkill: Cannot open RFKILL control device
,D/TCMD    (  441): NL - Read 1004 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/TCMD    (  441): NL - Read 1004 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/HeadsetStateMachine( 4975): max_hf_connections = 1
I/bluedroid( 4975): get_profile_interface handsfree
,D/HeadsetStateMachine( 4975): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
,D/BluetoothA2dp(  880): Proxy object connected
,D/A2dpService( 4975): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 4975): classInitNative: succeeds
,I/bluedroid( 4975): get_profile_interface avrcp
,E/RemoteController( 4975): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 4975): classInitNative: succeeds
D/A2dpStateMachine( 4975): make
,I/bluedroid( 4975): get_profile_interface a2dp
,I/GKI_LINUX( 4975): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
D/A2dpStateMachine( 4975): Enter Disconnected: -2
I/BluetoothHidServiceJni( 4975): classInitNative: succeeds
,I/libmdmdetect( 5020): ESOC framework not supported
E/Diag_Lib( 5020):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5020): baseband property is set to [msm]
I/libmdmdetect( 5020): ESOC framework not supported
,D/HidService( 4975): Received start request. Starting profile...
I/bluedroid( 4975): get_profile_interface hidhost
D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
,I/BluetoothHealthServiceJni( 4975): classInitNative: succeeds
,D/HealthService( 4975): Received start request. Starting profile...
,I/bluedroid( 4975): get_profile_interface health
,D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
I/BluetoothPanServiceJni( 4975): classInitNative(L105): succeeds
,D/PanService( 4975): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 4975): initializeNative(L110): pan
I/bluedroid( 4975): get_profile_interface pan
,E/wpa_supplicant( 5020):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5020): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5020): card_info[i].card_state: 0x0
E/wpa_supplicant( 5020): card_info[i].error_code: 0x0
E/wpa_supplicant( 5020): SIM/USIM not ready
E/wpa_supplicant( 5020): Error while reading SIM card status
,D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
E/wpa_supplicant( 5020): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5020): card_info[i].card_state: 0x0
E/wpa_supplicant( 5020): card_info[i].error_code: 0x0
E/wpa_supplicant( 5020): SIM/USIM not ready
I/wpa_supplicant( 5020): eap_proxy: Card not ready
,I/BtGatt.JNI( 4975): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 4975): handleDebugAction() action=null
,D/BtGatt.GattService( 4975): Received start request. Starting profile...
D/BtGatt.GattService( 4975): start()
,I/bluedroid( 4975): get_profile_interface gatt
D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
D/BtGatt.AdvertiseManager( 4975): advertise manager created
,W/ResourcesManager( 5014): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
,D/BluetoothMapService( 4975): Received start request. Starting profile...
D/BluetoothMapService( 4975): start()
,D/BluetoothMapEmailSettingsLoader( 4975): Found 0 applications
D/BluetoothMapEmailAppObserver( 4975): createReceiver()
,D/BluetoothMapEmailAppObserver( 4975): initObservers()
D/BluetoothMapEmailAppObserver( 4975): getEnabledAccountItems()
,D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
D/HeadsetStateMachine( 4975): Proxy object connected
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 4975): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 4975): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 4975): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 4975): enable
,I/GKI_LINUX( 4975): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 4975): init
,I/bt-btu  ( 4975): btu_task pending for preload complete event
,I/bt_vendor( 4975): bt-vendor : init
D/bt_userial_mct( 4975): userial_init
,I/bt_hwcfg( 4975): Starting hciattach daemon
I/bt_hwcfg( 4975): try to set false
,I/bt_hwcfg( 4975): Starting hciattach daemon
I/bt_hwcfg( 4975): try to set true
,I/qcom-bluetooth( 5049): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/Checkin ( 2983): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2983): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  880): Killing 4739:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/qcom-bluetooth( 5055): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5057): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/wpa_supplicant( 5020): Line 31: unknown global field '�'.
E/wpa_supplicant( 5020): Line 31: Invalid configuration line '�'.
I/wpa_supplicant( 5020): rfkill: Cannot open RFKILL control device
,D/TCMD    (  441): NL - Read 1004 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/qcom-bluetooth( 5059): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,E/wpa_supplicant( 5020): baseband property is set to [msm]
I/libmdmdetect( 5020): ESOC framework not supported
,I/qcom-bluetooth( 5060): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/wpa_supplicant( 5020):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5020): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5020): card_info[i].card_state: 0x0
E/wpa_supplicant( 5020): card_info[i].error_code: 0x0
E/wpa_supplicant( 5020): SIM/USIM not ready
E/wpa_supplicant( 5020): Error while reading SIM card status
,E/wpa_supplicant( 5020): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5020): card_info[i].card_state: 0x0
,E/wpa_supplicant( 5020): card_info[i].error_code: 0x0
E/wpa_supplicant( 5020): SIM/USIM not ready
I/wpa_supplicant( 5020): eap_proxy: Card not ready
I/wpa_supplicant( 5020): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,I/qcom-bluetooth( 5061): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/WifiStateMachine(  880): setSuspendOptimizations: 2 true
E/WifiStateMachine(  880): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  880): Supplicant connection established
,E/WifiStateMachine(  880): setWifiState: enabled
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_4739/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/AuthorizationBluetoothService( 1601): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiConfigStore(  880): Loading config and enabling all networks 
,E/WifiConfigStore(  880):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  880):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  880): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  880): Setting external_sim to 1
,D/WifiStateMachine(  880): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  880): startHal
,E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2ddb89c
D/wifi    (  880): halHandle = 0x0, mVM = 0xb7d48310, mCls = 0x20179e
I/WifiNative-HAL(  880): Could not start hal
E/WifiStateMachine(  880): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 5020): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/wpa_supplicant( 5020): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5067 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,E/native  (  880): do suspend true
,D/WifiP2pService(  880): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  299): Setting iface cfg
D/CommandListener(  299): Trying to bring up p2p0
,D/WifiScanningService(  880): SCAN_AVAILABLE : 3
D/RttService(  880): SCAN_AVAILABLE : 3
D/WifiScanningService(  880): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa1b119cc
D/wifi    (  880): halHandle = 0x0, mVM = 0xb7d48310, mCls = 0x101552
I/WifiNative-HAL(  880): Could not start hal
E/WifiScanningService(  880): could not start HAL
,D/WifiMonitor(  880): startMonitoring(p2p0) with mConnected = true
D/RttService(  880): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnablingState
D/WifiP2pService(  880): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2p socket connection successful
D/WifiP2pService(  880): P2pEnabledState
D/WifiP2pService(  880): sending p2p connection changed broadcast
,D/WifiNative-HAL(  880): p2pGetDeviceAddress
,D/WifiNative-HAL(  880): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,E/WifiStateMachine(  880): set country code US
,D/WifiP2pService(  880): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  880): MCC mode enabled 0
,D/WifiP2pService(  880): mP2pAutoConnectSupport = 0
,E/WifiStateMachine(  880): set frequency band 2
,D/WifiP2pService(  880): sending p2p persistent groups changed broadcast
D/WifiP2pService(  880): InactiveState
D/WifiP2pService(  880): InactiveState{ when=-5ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-5ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 5020): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 5020): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiP2pService(  880): InactiveState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/SharedPreferencesImpl(  880): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 5067): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 4765:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/Checkin ( 2983): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  306): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  306): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): wifi_connect_to_supplicant, current pid is = 306
,D/MDMCTBK (  306): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  306): wifi_close_sockets: Exit
,E/MDMCTBK (  306): Attach monitor thread
,I/MDMCTBK (  306): createWifiMonitorThread: Started the wifi monitor thread -1197830416
D/MDMCTBK (  306): wifi_wait_on_socket: Enter monitor thread
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_4765/cgroup.procs: No such file or directory
,D/Checkin ( 2983): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  441): NL - Read 1004 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  306): Event received = WPS-AP-AVAILABLE 
,I/WifiNative-HAL(  880): startHal
E/wifi    (  880): getStaticLongField sWifiHalHandle 0xa2ddb8fc
D/wifi    (  880): halHandle = 0x0, mVM = 0xb7d48310, mCls = 0x17be
I/WifiNative-HAL(  880): Could not start hal
E/WifiStateMachine(  880): [1,449,007,438,060 ms] noteScanEnd no scan source
E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@6757b47 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  880):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  880): will read network variables netId=0
,E/WifiStateMachine(  880): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  880): will read network variables netId=0
,I/wpa_supplicant( 5020): wlan0: Trying to associate with SSID 'NG700'
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  306): Event received = Trying to associate with
D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 5020): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiConfigStore(  880): setLastSelectedConfiguration -1
,E/wpa_supplicant( 5020): PNO: In assoc process
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  441): NL - Read 312 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 192 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 68 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/TCMD    (  441): NL - Read 1004 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 80 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 80 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
D/TCMD    (  441): NL - Read 68 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5020): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  306): Event received = Associated with c0:ff:d4
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
,E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5020): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  306): Event received = WPA: Key negotiation com
I/wpa_supplicant( 5020): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  306):  STA Connected !!
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/TCMD    (  441): NL - Read 1004 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,E/MDMCTBK (  306): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2462, reply_len: 4, ret: 0
D/MDMCTBK (  306): get_freq !!, resp=2462
I/MDMCTBK (  306): get_freq !!, Strip data
I/MDMCTBK (  306): get_freq !!, band = 2, freq = 2462
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
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
I/MDMCTBK (  306): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 0, data=0
I/MDMCTBK (  306): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  306): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197814560
I/MDMCTBK (  306): return from set_get_from_wpa_supplicant
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  306): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  306): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  306): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  306): , reply_len: 3, ret: 0
,E/MDMCTBK (  306): MdmCutbackHndler, resp=OK
E/MDMCTBK (  306): 
D/MDMCTBK (  306): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/qcom-bluetooth( 5106): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/qcom-bluetooth( 5108): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledStateupdate channel list
D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  299): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 1
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  880): do suspend false
,E/wpa_supplicant( 5020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 5020): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d22d9e7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3d22d9e7 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
I/bt_hwcfg( 4975): bluetooth satus is on
D/bt_userial_mct( 4975): userial_open(port:0)
I/bt_userial_vendor( 4975): Done intiailizing UART
I/bt_userial_vendor( 4975): Done intiailizing UART
,I/bt_userial_mct( 4975): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 4975): Bluetooth Firmware and smd is initialized
,I/bt-btu  ( 4975): btu_task received preload complete event
D/bt_userial_mct( 4975): Entering userial_read_thread()
,I/        ( 4975): BTE_InitTraceLevels -- TRC_HCI
I/        ( 4975): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 4975): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 4975): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 4975): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 4975): BTE_InitTraceLevels -- TRC_A2D
I/        ( 4975): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 4975): BTE_InitTraceLevels -- TRC_BTM
I/        ( 4975): BTE_InitTraceLevels -- TRC_GAP
I/        ( 4975): BTE_InitTraceLevels -- TRC_PAN
I/        ( 4975): BTE_InitTraceLevels -- TRC_SDP
I/        ( 4975): BTE_InitTraceLevels -- TRC_GATT
I/        ( 4975): BTE_InitTraceLevels -- TRC_SMP
,I/        ( 4975): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 4975): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 4975): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6d7fd85 
E/bt-btm  ( 4975): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6d7fd85 
,E/bt-btif ( 4975): Calling BTA_HhEnable
E/bt-btif ( 4975): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 4975): Address is:44:80:EB:7B:5A:05
,D/BluetoothAdapterProperties( 4975): Name is: XT1072
,D/BluetoothManagerService(  880): Bluetooth Adapter name changed to XT1072
D/BluetoothAdapterProperties( 4975): Scan Mode:20
D/BluetoothAdapterProperties( 4975): Discoverable Timeout:120
D/BluetoothManagerService(  880): Stored Bluetooth name: XT1072
,D/BluetoothAdapterProperties( 4975): Adding bonded device:7C:F9:0E:37:96:AB
,E/BluetoothRemoteDevices( 4975): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/bt_mct  ( 4975): hci lib postload completed
,D/bte_conf( 4975): Device ID record 1 : primary
D/bte_conf( 4975):   vendorId            = 000f
D/bte_conf( 4975):   vendorIdSource      = 0001
D/bte_conf( 4975):   product             = 1200
D/bte_conf( 4975):   version             = 1436
D/bte_conf( 4975):   clientExecutableURL = 
D/bte_conf( 4975):   serviceDescription  = 
D/bte_conf( 4975):   documentationURL    = 
D/bte_conf( 4975): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 4975): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 4975): ScanMode =  20
D/BluetoothPanServiceJni( 4975): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 4975): State =  11
D/BluetoothAdapterProperties( 4975): Setting state to 12
I/BluetoothAdapterState( 4975): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  880): Message: 60
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  880): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothA2dp(  880): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 4975): Entering On State
,D/BluetoothHeadset( 1504): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  880): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 4975): Scan Mode:21
,D/BluetoothAdapterProperties( 4975): Discoverable Timeout:120
D/BluetoothHeadset( 1539): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1504): onBluetoothStateChange: up=true
D/BluetoothManagerService(  880): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  880): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  880): Message: 40
D/BluetoothManagerService(  880): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 4975): onReceive
,D/BluetoothMapService( 4975): STATE_ON
,D/BluetoothMapMasInstance( 4975): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 4975): MAS initSocket()
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4975): getBluetoothService() called with no BluetoothManagerCallback
,I/Telecom ( 1504): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapMasInstance( 4975): Accepting socket connection...
,D/HeadsetStateMachine( 4975): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 4975): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/HeadsetStateMachine( 4975): mNumber:  mType: 128
D/HeadsetStateMachine( 4975): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 4975): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/ContextImpl( 5014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3887b00:true
,D/LocalBluetoothProfileManager( 5014): Adding local A2DP profile
,D/BluetoothManagerService(  880): Message: 30
,D/AuthorizationBluetoothService( 1601): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 4975): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 5014): Adding local HEADSET profile
D/BluetoothManagerService(  880): Message: 30
,D/BluetoothManagerService(  880): Message: 30
,D/BluetoothManagerService(  880): Message: 30
,D/LocalBluetoothProfileManager( 5014): Adding local MAP profile
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothMap( 5014): Create BluetoothMap proxy object
,D/BluetoothManagerService(  880): Message: 30
,D/BluetoothManagerService(  880): Message: 30
,W/BluetoothAdapter( 4975): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 5014): LocalBluetoothProfileManager construction complete
,I/BtOppRfcommListener( 4975): Accept thread started.
,D/DockEventReceiver( 5014): finishStartingService: stopping service
,D/BluetoothA2dp( 5014): Proxy object connected
,D/A2dpProfile( 5014): Bluetooth service connected
,D/BluetoothHeadset( 5014): Proxy object connected
,D/HeadsetProfile( 5014): Bluetooth service connected
,D/BluetoothInputDevice( 5014): Proxy object connected
,D/HidProfile( 5014): Bluetooth service connected
,D/BluetoothPan( 5014): BluetoothPAN Proxy object connected
,D/PanProfile( 5014): Bluetooth service connected
,D/BluetoothMap( 5014): Proxy object connected
,D/MapProfile( 5014): Bluetooth service connected
,D/BluetoothMap( 5014): getConnectedDevices()
,D/BluetoothPbap( 5014): Proxy object connected
,D/PbapServerProfile( 5014): Bluetooth service connected
,E/DHCPCD  ( 5125): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5125): version 5.5.6 starting
,E/DHCPCD  ( 5125): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5125): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5125): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5125): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 5125): wlan0: rebinding lease of 192.168.1.134
,D/DHCPCD  ( 5125): wlan0: sending REQUEST (xid 0xafba0777), next in 4.68 seconds
,V/AlarmManager(  880): send {c5531f4, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {c5531f4, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,I/DHCPCD  ( 5125): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/DHCPCD  ( 5125): wlan0: leased 192.168.1.134 for 86400 seconds
D/DHCPCD  ( 5125): wlan0: adding IP address 192.168.1.134/24
D/DHCPCD  ( 5125): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5125): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5125): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5125): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/TCMD    (  441): NL - Read 60 bytes from update socket.
D/TCMD    (  441): NL - ignore NL message, type = 20
D/TCMD    (  441): Listening for incoming client connection request
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4910): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 4910): 
I/jxcore-log( 4910): my name is : motorola-XT1072_PT7532
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): attempting to connect to test coordinator
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): check test folder
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): found test : ./testFindPeers.js
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): found test : ./testReConnect.js
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): found test : ./testSendData.js
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): Test app app.js loaded
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/chromium( 4910): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.134
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,D/ConnectivityService(  880): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 100
,E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  880): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  880):    accepting network in place of null
,D/ConnectivityService(  880): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1520): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1943): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Dec 2015 22:04:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449007440452], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449007440433]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1943): CM callback handler got msg 524290
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1520): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1520): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1520): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1520): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1943): CM callback handler got msg 524295
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2572): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1452): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2572): now: 199942 ,futureTime: 9223372036854775807
,D/PollingManager( 2572): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5203 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2572): now: 199980 ,futureTime: 9223372036854775807
,D/PollingManager( 2572): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1452): now: 200000 ,futureTime: 86472224
D/Central_PollingManager( 1452): Polling alarm set to expire at: 86472224 Current Time: 200000
,D/AlarmManagerService(  880): Setting time of day to sec=1449007444
,W/AlarmManagerService(  880): Unable to set rtc to 1449007444: Invalid argument
,V/AlarmManager(  880): send {187c3d62, *alarm*:android.intent.action.TIME_TICK}
,D/PollingManager( 2572): now: 200049 ,futureTime: 9223372036854775807
,V/AlarmManager(  880): done {187c3d62, *alarm*:android.intent.action.TIME_TICK} [64ms]
,I/MDMCTBK (  306): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  306): NetlinkHandler, interfaceAdded
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
E/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  306): , Wifi = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 1, data=0
I/MDMCTBK (  306): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  306): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197814560
I/MDMCTBK (  306): return from set_get_from_wpa_supplicant
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  306): set_property_value, Enter
D/MDMCTBK (  306): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  306): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  306): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  306): , reply_len: 3, ret: 0
E/MDMCTBK (  306): MdmCutbackHndler, resp=OK
E/MDMCTBK (  306): 
D/MDMCTBK (  306): wifi_set_tx_pwr: Exit
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:1, mf:0, chrg:1
,I/MDMCTBK (  306): send SAR ctrl over QMI
D/OtaApp  ( 2572): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2572): [debug] > PollingManagerService, now: 200127 ,futureTime: 46199557
D/OtaApp  ( 2572): [debug] > Polling alarm set to expire at: 46199557 Current Time: 200128
,D/MMApiProvisionService( 2572): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2572): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2572): createDeviceIdOrLogin update_device
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2572): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2572): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2572): isDeviceProvisioned: deviceId = 2072049230914535424
,E/GpsLocationProvider(  880): No APN found to select.
,I/art     ( 2572): Explicit concurrent mark sweep GC freed 14655(919KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.095ms total 73.327ms
,I/art     ( 1452): Explicit concurrent mark sweep GC freed 4666(208KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 716us total 30.625ms
,D/GpsLocationProvider(  880): NTP server returned: 1449007444450 (Tue Dec 01 23:04:04 GMT+01:00 2015) reference: 200004 certainty: 14 system time offset: -359
,E/LocSvc_ApiV02(  880): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,I/art     (  880): Explicit concurrent mark sweep GC freed 46832(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 2.563ms total 135.428ms
,D/CCE     ( 2572): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2572): createDeviceIdOrLogin update_device
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2572): generating token using payload instead of using session token
,D/MMApiProvisionService( 2572): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2572): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiWebService( 2572): Received data connectivity intent from PollingManager .. retry the waiting requests: 1
,D/MMApiWebService( 2572): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/MusicStore( 5203): Database version: 120
,D/MMApiProvisionService( 2572): isDeviceProvisioned: deviceId = 2072049230914535424
,D/ Nonce  ( 2572):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/CCE     ( 2572): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2572): createDeviceIdOrLogin update_device
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2572): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2572): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2572): [debug] > CusSM.onRadioUp
,I/GoogleURLConnFactory( 1601): Using platform SSLCertificateSocketFactory
,D/OtaApp  ( 2572): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2572): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2572): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2572): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2572): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2572): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2572): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 2572): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 2572): doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5203): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5203): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5203): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Auth.Api.Credentials( 1943): [CredentialSyncAdapter] Unknown sync event.
,W/ResourcesManager( 5203): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5203): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PerfProfileCollectorService( 1943): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1943): removeStateFiles() called
,D/PerfProfileCollectorService( 1943): User is not opt-in to Usage & Diagnostics.
,V/JNIHelp ( 5203): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 5203): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5203): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cedea6b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5203): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5203): GMSCore installation verified
,I/ConfigStore( 5203): Config Database version: 1
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 4814): Attempt to remove local handle scope entry from IRT, ignoring
,I/MediaRouter( 5203): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5203): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5203): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5203): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5283 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 5203): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 5203): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 4910): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 4910): 
,I/VacuumService( 1601): Vacuum at: now=1449007445952 tag=VacuumService
,V/Mms     ( 5283): mnc/mcc: 
,V/Mms     ( 5283): tag: int value: recipientLimit - 20
V/Mms     ( 5283): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5283): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5283): tag: int value: maxSubjectLength - 80
V/Mms     ( 5283): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5283): tag: bool value: enableGroupMms - false
V/Mms     ( 5283):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 5283): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5311 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/MMApiWSBase( 2572): doRequest(): v1/gns/list/messages resp length: 1363
,D/CCE     ( 2572): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 2572): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ Nonce  ( 2572):  Nonce Reponse 
D/        ( 2572): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"021d77bf-38b7-4ed8-8213-6e35cf3ca6e5"}
D/MMApiWSBase( 2572): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2572):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2572): mOutstandingReq set to false
,I/ActivityManager(  880): Start proc com.google.android.calendar for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService: pid=5329 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/PhenotypeConfigurator( 1601): Server returned 404
,D/Checkin ( 2572): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 2572): handleGetNotificationsResponse(): got 0; more=false
,I/art     (  880): Explicit concurrent mark sweep GC freed 19908(864KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.681ms total 130.695ms
,D/MMApiProvisionService( 2572):  pTime 1448876947330 sExp 172742 cTime 1449007446400 tTime 1449049689330
D/MMApiProvisionService( 2572):  No login Required 
,I/art     ( 1539): Explicit concurrent mark sweep GC freed 29918(1921KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.038ms total 79.008ms
,D/PhoneMonitor( 5311): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5311): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5311): onReceive CONNECTIVITY_CHANGE networkType=1
E/SQLiteLog( 5329): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
I/ActivityManager(  880): Killing 4664:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_4664/cgroup.procs: No such file or directory
,I/CheckinService( 1943): Checkin interval check for package: unspecified last checkin: 1448988222100 min interval config: 0 actual interval: 19224391
,I/CheckinService( 1943): Checking schedule, now: 1449007446498 next: 1448988252069
,I/CheckinService( 1943): active receiver: enabled
,I/CheckinService( 1943): Preparing to send checkin request
,I/EventLogService( 1943): Accumulating logs since 1449007182958
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5356 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5356): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/iu.SyncManager( 1943): SYNC; picasa accounts
,D/UdcCache:FPQuery( 1943): Bootstrapping UDC settings cache for all accounts
,D/NetworkLogImpl( 1943): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1943): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1943): num queued entries: 0
I/iu.UploadsManager( 1943): num updated entries: 0
,I/iu.SyncManager( 1943): NEXT; no task
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/AbstractGoogleClient( 5329): Application name is not set. Call Builder#setApplicationName.
,I/CalendarProvider2( 5356): Created com.android.providers.calendar.CalendarAlarmManager@c5a97f9(com.android.providers.calendar.CalendarProvider2@2076c33e)
,W/DataUsage( 2572): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/art     ( 1601): Explicit concurrent mark sweep GC freed 37561(2MB) AllocSpace objects, 4(87KB) LOS objects, 40% free, 11MB/19MB, paused 10.807ms total 124.523ms
,E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1456a14c)
,E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1ad00595)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3283f6aa)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@28d4029b)
,E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19f28638)
,W/DataUsage( 2572): invalid counter update blocked: 'err' by 0
I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5387 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/Checkin ( 2572): publish the event [tag = MOT_CCE event name = LOG]
,I/AnalyticsLogBase( 5329): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 5329): PlayLogger.onLoggerConnected
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,I/GCM     ( 1601): GCM config loaded
,I/GCM     ( 1601): Ack for not saved message 20
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5423 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 4410:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_4410/cgroup.procs: No such file or directory
,W/ResourcesManager( 5423): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5356): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5356): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/GetConfigurationSnapshotOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/CalendarSyncAdapter( 5329): Found no pending settings
,I/ActivityManager(  880): Killing 5014:com.android.settings/1000 (adj 15): empty #7
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,W/libprocessgroup(  880): failed to open /acct/uid_1000/pid_5014/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5067:com.motorola.context/u0a8 (adj 15): empty #7
,I/PhenotypeFlagCommitter( 1601): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 1601): Using platform SSLCertificateSocketFactory
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_5067/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  880): Killing 5203:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/Babel_SMS( 5423): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5423): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5423): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5423): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5423): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5423): MmsConfig.loadFromResources
,E/Babel_SMS( 5423): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5423): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     (  880): Explicit concurrent mark sweep GC freed 15137(665KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.736ms total 130.436ms
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_5203/cgroup.procs: No such file or directory
,W/Settings( 5423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5423): startup - clean
,I/Babel   ( 5423): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5467 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 22.088ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 20.128ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 21.786ms
,W/VideoCapabilities( 5423): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5423): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5423): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5423): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5423): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5423): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5423): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5423): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5488 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/vclib   ( 5423): onServiceConnected
W/Babel   ( 5423): Attempted to change video mute state without an active call.
,W/ResourcesManager( 5488): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5488): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 5423): connection state changed from UNKNOWN to CONNECTED
,I/MultiDex( 5488): VM with version 2.1.0 has multidex support
I/MultiDex( 5488): install
I/MultiDex( 5488): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5488): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/CalendarSyncAdapter( 5329): Found no pending settings
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5467): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/ActivityThread( 5488): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5488): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3fd2fe50: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5488): Installed default security provider GmsCore_OpenSSL
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5467): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  880): Killing 5283:com.android.mms/u0a23 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5467): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 5467): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5467):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5467):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5467): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_5283/cgroup.procs: No such file or directory
,W/GAv4    ( 5467): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 5488): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 5488): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
W/GAv4    ( 5467): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5467): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/WVCdm   (  308): Instantiating CDM.
I/WVCdm   (  308): CdmEngine::OpenSession
,I/WVCdm   (  308): Level3 Library Sep 25 2014 17:10:03
,D/NativeLibraryUtils( 5488): Install completed successfully. count=13 extracted=0
,W/WVCdm   (  308): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  308): Service_Initialize: starts!
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
E/QSEECOMAPI: (  308): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,E/QSEECOMAPI: (  308): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  308): App is not loaded in QSEE
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d76000
,E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d76000
,I/GoogleURLConnFactory( 5488): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb5060960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb7e24310, dataLength=8
,D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7d347f0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e618a0, idLength=0xbeac12b0
,D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  308): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  308): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=1104106385
,D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e15f30
D/DrmWidevineDash(  308): message_length=1591, signature=0xb7da0e30, signature_length=3198947988
,I/WebViewFactory( 5467): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5467): Time to load native libraries: 1 ms (timestamps 5002-5003)
I/LibraryLoader( 5467): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5467): Binding Chromium to main looper Looper (main, tid 1) {2b0a9b80}
,I/LibraryLoader( 5467): Expected native library version number "",actual native library version number ""
,I/chromium( 5467): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 5467): Initializing chromium process, singleProcess=true
,W/art     ( 5467): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5467): ApplicationContext is null in ApplicationStatus
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
D/DrmWidevineDash(  308): OEMCrypto_Terminate: ends! returns 0
,W/chromium( 5467): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5467): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5467): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5467): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5467): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5467): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5467): Local Branch: 
I/Adreno-EGL( 5467): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5467): Local Patches: NONE
I/Adreno-EGL( 5467): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 5467): Requires BLUETOOTH permission
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/NSApplication( 5467): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5568 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5311:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_5311/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  880): Killing 5387:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_5387/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2572): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 2572): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
E/SQLiteLog( 2572): (284) automatic index on registration(APP_ID)
,D/WaitableIntentService( 2572): ServiceHandler.handleMessage: mWaitCount=1
,I/PushService( 2572): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.receiver.DateChangeBroadcastReceiver: pid=5599 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
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
,E/QSEECOMAPI: (  308): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  308): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  308): App is not loaded in QSEE
,W/ResourcesManager( 5599): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/QSEECOMAPI: (  308): Loaded image: APP id = 3
,D/DrmWidevineDash(  308): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  308): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d76000
E/DrmWidevineDash(  308): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4d76000
,D/DrmWidevineDash(  308): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  308): hlos api version =  9
D/DrmWidevineDash(  308): tz api version =  8
D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  308): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  308): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  308): OEMCrypto_OpenSession: starts! SID=0xb5606960
D/DrmWidevineDash(  308): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  308): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: starts! randomData=0xb7e2cc70, dataLength=8
D/DrmWidevineDash(  308): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7d44130, wrapped_rsa_key_length=1280
W/Uploader( 1601):  no longer exists, so no auth token.
D/DrmWidevineDash(  308): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  308): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  308): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  308): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  308): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  308): OEMCrypto_GetDeviceID: starts! deviceID=0xb7e618e0, idLength=0xb5060730
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
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
,D/DrmWidevineDash(  308): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  308): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  308): PrepareKeyRequest: nonce=4141398813
D/DrmWidevineDash(  308): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e15f30
D/DrmWidevineDash(  308): message_length=1626, signature=0xb7da0e30, signature_length=3037071124
,I/ActivityManager(  880): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=5620 uid=10096 gids={50096, 9997} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 5423:com.google.android.talk/u0a70 (adj 15): empty #7
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
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_5423/cgroup.procs: No such file or directory
,I/System.out( 5620): TimeService: Loaded Library 
D/TimeService( 5620): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449007450606
,D/        ( 5620): TimeServiceNative: User Time to be set is 1449007450606
D/QC-time-services( 5620): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 5620): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 5620): Lib:time_genoff_operation: pargs->ts_val = 1449007450606
D/QC-time-services( 5620): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  329): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  329): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449007450606
D/QC-time-services(  329): Daemon:genoff_opr: Base = 2, val = 1449007450606, operation = 0
D/QC-time-services(  329): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/1/115 22:2:59
D/QC-time-services(  329): Daemon:Value read from RTC seconds = 1449007379000
D/QC-time-services(  329): Daemon:new time 1449007450606 
D/QC-time-services(  329): Daemon: delta 71606 genoff 71606 
D/QC-time-services(  329): Daemon:genoff_persistent_update: Writing genoff = 71606 to memory
D/QC-time-services(  329): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  329): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  329): Updating the TOD offset
,D/QC-time-services(  329): Daemon:genoff_persistent_update: Writing genoff = 71606 to memory
D/QC-time-services(  329): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  329): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  329): Daemon:Update to modem bit set
,D/QC-time-services(  329): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  329): Daemon: Base = 2, Value being sent to MODEM = 18446743757744823222
E/QC-time-services( 5620): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  880): Killing 5467:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,E/QC-time-services(  329): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  329): Daemon: Time-services: Waiting to acceptconnection
,I/dex2oat ( 5639): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_5467/cgroup.procs: No such file or directory
,I/CheckinService( 1943): Checkin interval check for package: unspecified last checkin: 1448988222100 min interval config: 0 actual interval: 19228823
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dex2oat ( 5639): dex2oat took 136.291ms (threads: 4)
,I/Adreno-EGL( 5488): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5488): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5488): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5488): Local Branch: 
I/Adreno-EGL( 5488): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5488): Local Patches: NONE
I/Adreno-EGL( 5488): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=5649 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Adreno-EGL( 5488): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5488): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5488): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5488): Local Branch: 
I/Adreno-EGL( 5488): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5488): Local Patches: NONE
I/Adreno-EGL( 5488): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 5488): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5488): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5488): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5488): Local Branch: 
I/Adreno-EGL( 5488): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5488): Local Patches: NONE
I/Adreno-EGL( 5488): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:33000 mC
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/GAv4    ( 5649): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5649):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5649):   adb logcat -s GAv4
,W/GAv4    ( 5649): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 5488): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5488): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5488): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5488): Local Branch: 
I/Adreno-EGL( 5488): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5488): Local Patches: NONE
I/Adreno-EGL( 5488): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 5649): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5649): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  880): Killing 5356:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_5356/cgroup.procs: No such file or directory
,D/OtaApp  ( 2572): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2572): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2572): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/OtaApp  ( 2572): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2572): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2572): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2572): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1452): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2572): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2572): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2572): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2572): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,W/ContextImpl( 5329): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5329): Thread[GAThread,5,main]: No campaign data found.
,I/SundryService( 2572): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2572): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2572): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2572): ServiceHandler.handleMessage: mWaitCount=0
,W/IInputConnectionWrapper( 4910): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5682 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     ( 1601): Explicit concurrent mark sweep GC freed 73305(4MB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 12MB/21MB, paused 9.074ms total 121.764ms
,I/art     ( 1943): Explicit concurrent mark sweep GC freed 26344(1795KB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 14MB/23MB, paused 1.294ms total 222.270ms
,D/GetNotificationsWS( 2572): unbindWebServices(): un-registering our AIDL callback...
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,223
,W/ResourcesManager( 5682): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/CheckinTask( 1943): Sending checkin request (9469 bytes)
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Babel_SMS( 5682): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5682): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5682): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5682): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5682): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5682): MmsConfig.loadFromResources
,E/Babel_SMS( 5682): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5682): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5682): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5682): startup - clean
,I/Babel   ( 5682): deleted: false for 0
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5719 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinResponseProcessor( 1943): From server: 1 gservices updates and 0 deletes
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5682): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5682): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5682): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5682): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 5568:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  880): Explicit concurrent mark sweep GC freed 21637(945KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 3.566ms total 130.293ms
,I/CertBlacklister(  880): Certificate blacklist changed, updating...
,I/CertBlacklister(  880): Certificate blacklist updated
,I/GservicesProvider( 1601): main difference update completed
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_5568/cgroup.procs: No such file or directory
,I/vclib   ( 5682): onServiceConnected
W/Babel   ( 5682): Attempted to change video mute state without an active call.
,I/CheckinRequestBuilder( 1943): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1943): Failed to find provider info for com.google.android.wearable.settings
,I/MDMCTBK (  306): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  306): NetlinkHandler, interfaceAdded
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
E/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  306): , Wifi = 1
I/MDMCTBK (  306): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  306): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
I/MDMCTBK (  306): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  306): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  306): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): get_property_value, Enter
I/MDMCTBK (  306): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  306): get_property_value, Exit
I/MDMCTBK (  306): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197814560
I/MDMCTBK (  306): return from set_get_from_wpa_supplicant
I/MDMCTBK (  306): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
D/MDMCTBK (  306): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  306): set_property_value, Enter
I/MDMCTBK (  306): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  306): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  306): , reply_len: 3, ret: 0
E/MDMCTBK (  306): MdmCutbackHndler, resp=OK
E/MDMCTBK (  306): 
D/MDMCTBK (  306): wifi_set_tx_pwr: Exit
I/MDMCTBK (  306): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  306): set_property_value, Exit
E/MDMCTBK (  306): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5750 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GetCommittedConfigurationOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/ResourcesManager( 5750): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5750): Created com.android.providers.calendar.CalendarAlarmManager@c5a97f9(com.android.providers.calendar.CalendarProvider2@2076c33e)
,D/WearableService( 1709): callingUid 10016, callindPid: 1709
,E/MDM     ( 1709): [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1601): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 1943): Restart initialization of location
,I/CheckinRequestBuilder( 1943): Classify the device as Phone.
,D/AuthorizationBluetoothService( 1601): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1943): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1709): No location to return for getLastLocation()
,W/FusedLocationProvider( 1601): location=null
,I/CheckinTask( 1943): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=5786 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/CheckinService( 1943): Checking schedule, now: 1449007452947 next: 1449608589893
I/CheckinService( 1943): active receiver: disabled
I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,D/CheckinService( 1943): Recording last checkin time for package unspecified as 1449007452968
,I/ActivityManager(  880): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=5812 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,E/UpdateRequestReceiver( 5812): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5812): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5812): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5812): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=5841 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 4814:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  322): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 25.093ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.631ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.361ms
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_4814/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5620:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10096/pid_5620/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5750): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5750): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Killing 5649:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10055/pid_5649/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5682:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_5682/cgroup.procs: No such file or directory
,I/GservicesUpdateTask( 5841): Updating Gservices keys
,I/art     ( 1601): Explicit concurrent mark sweep GC freed 45952(2MB) AllocSpace objects, 11(231KB) LOS objects, 40% free, 11MB/19MB, paused 1.165ms total 114.771ms
,I/art     ( 1943): Explicit concurrent mark sweep GC freed 16532(1068KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/23MB, paused 1.179ms total 86.698ms
,W/SQLiteConnectionPool( 1943): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/SystemEventReceiver( 1943): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1943): Updating ocr activity enabled=false
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,W/ActivityManager(  880): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/art     ( 1601): Explicit concurrent mark sweep GC freed 6004(239KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/19MB, paused 1.271ms total 75.156ms
,I/art     (  880): Explicit concurrent mark sweep GC freed 15396(743KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.643ms total 121.405ms
,I/CheckinService( 1943): Checkin interval check for package: unspecified last checkin: 1449007452968 min interval config: 0 actual interval: 1664
,I/CheckinService( 1943): Checking schedule, now: 1449007454647 next: 1449608589893
I/CheckinService( 1943): active receiver: disabled
,I/SystemUpdateService( 1943): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1943): onCreate
,D/SystemUpdateService( 1943): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/OcrModelManager( 1943): Updating downloaded model state (gservices changed)
,I/SystemUpdateService( 1943): cancelUpdate (empty URL)
I/SystemUpdateService( 1943): active receiver: disabled
,D/GCM     ( 1601): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/SystemUpdateService( 1943): onDestroy
,I/GCoreUlr( 1709): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1709): DispatchingService.onCreate()
,I/GCoreUlr( 1709): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5918 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/GCoreUlr( 1709): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1709): Unbound from all location providers
,I/GCoreUlr( 1709): DispatchingService.onDestroy()
I/GCoreUlr( 1709): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1709): Unbound from all location providers
,D/PhoneMonitor( 5918): Register our PhoneStateListener
,V/SetupWizard( 5918): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 5750:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_5750/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1601): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1601): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5942 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5942): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5942): Created com.android.providers.calendar.CalendarAlarmManager@c5a97f9(com.android.providers.calendar.CalendarProvider2@2076c33e)
,I/ActivityManager(  880): Killing 5812:com.google.android.configupdater/u0a54 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10054/pid_5812/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5942): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5942): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Killing 5786:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_5786/cgroup.procs: No such file or directory
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1539): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5975 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5975): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5975): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5975): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5975): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5975): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5975): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5975): MmsConfig.loadFromResources
,E/Babel_SMS( 5975): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5975): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,V/GmsNetworkLocationProvi( 1709): DISABLE
,W/Settings( 5975): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/GCoreNlp( 1709): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel_Crash( 5975): startup - clean
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Babel   ( 5975): deleted: false for 0
,I/Launcher( 1556): Deferring update until onResume
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6013 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1563d53a
,I/art     ( 1709): Explicit concurrent mark sweep GC freed 17074(979KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 11MB/18MB, paused 7.988ms total 82.310ms
,E/DataBuffer( 1709): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3083d959)
,W/VideoCapabilities( 5975): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5975): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5975): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5975): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5975): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5975): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5975): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5975): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 6013): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  880): Explicit concurrent mark sweep GC freed 18893(953KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.864ms total 118.901ms
,I/vclib   ( 5975): onServiceConnected
W/Babel   ( 5975): Attempted to change video mute state without an active call.
,W/ResourcesManager( 5975): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5975): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6035 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5719:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_5719/cgroup.procs: No such file or directory
,W/asset   ( 6035): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6035): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6035): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6035): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,V/JNIHelp ( 5975): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 5975): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5975): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6055 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 5918:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_5918/cgroup.procs: No such file or directory
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,D/Finsky  ( 6055): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6055): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6055): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6055): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 6055): Skipping gmscore version check
,D/Finsky  ( 6055): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6055): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6055): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/UpdateIcingCorporaServi( 5841): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1556): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@18224d31 new=com.google.android.velvet.VelvetApplication@18224d31
,D/Finsky  ( 6055): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6107 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 1943): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1943): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6107): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5841): UpdateCorporaTask done [took 232 ms] updated apps [took 232 ms] 
,I/ActivityManager(  880): Killing 5488:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_5488/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 5599:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_5599/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  880): Killing 5942:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_5942/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6145 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6145): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6145): Created com.android.providers.calendar.CalendarAlarmManager@c5a97f9(com.android.providers.calendar.CalendarProvider2@2076c33e)
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,W/PackageSettings(  880): Skipping PackageSetting{13a978a4 com.example.hello/10333} due to missing metadata
,I/CalendarProvider2( 6145): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6145): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6173 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 5975:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_5975/cgroup.procs: No such file or directory
,W/ResourcesManager( 6173): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Killing 6035:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_6035/cgroup.procs: No such file or directory
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310873, SEQNUM=4468, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-366, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,I/ActivityManager(  880): Waited long enough for: ServiceRecord{3b845287 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ActivityManager(  880): Killing 5841:com.google.android.googlequicksearchbox:search/u0a39 (adj 13): empty #7
,I/ActivityManager(  880): Killing 6055:com.android.vending/u0a32 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_5841/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6055/cgroup.procs: No such file or directory
,V/AlarmManager(  880): send {2eac9945, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {2eac9945, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311276, SEQNUM=4472, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13020, POWER_SUPPLY_CHARGE_COUNTER=-421, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1709): disconnect managed GoogleApiClient
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,V/AlarmManager(  880): send {68e789a, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {68e789a, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [67ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310904, SEQNUM=4474, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-479, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
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
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1601): onCreate
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
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
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
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
,I/ConfigService( 1601): onDestroy
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/ClearcutLoggerApiImpl( 1601): disconnect managed GoogleApiClient
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector connect called
I/jxcore-log( 4910): 
I/jxcore-log( 4910): Coordinator is now connected to the server!
I/jxcore-log( 4910): 
,I/chromium( 4910): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310771, SEQNUM=4478, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-874, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {187c3d62, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {187c3d62, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 4910): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): DBG, CoordinatorConnector command called
I/jxcore-log( 4910): 
I/jxcore-log( 4910): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"90:E7:C4:F6:69
I/jxcore-log( 4910): Start now : testSendData.js
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): check server
I/jxcore-log( 4910): 
I/jxcore-log( 4910): serverPort is 52111
I/jxcore-log( 4910): 
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4910): Stoping All
,I/        ( 4910): Stopping services
I/        ( 4910): Stop Bluetooth
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4910): Start-My BT: 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 4910):  mInstanceString : {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}
,I/        ( 4910): All stuff available and enabled
I/        ( 4910): Stoping All
I/        ( 4910): Stopping services
I/        ( 4910): Stop Bluetooth
I/        ( 4910): Starting All
I/        ( 4910): Stopping services
I/        ( 4910): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@2fc96bba
I/        ( 4910): Stopping services
I/        ( 4910): Starting services address: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}
,I/        ( 4910): Add local service :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}, length : 81
,D/WifiP2pService(  880): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@aab8a796 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@aab8a796 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service
,D/WifiP2pService(  880): add a new client
,I/        ( 4910): peerDiscoveryTimer timeout value:8078
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4910): Stop Bluetooth
,I/        ( 4910): StartBluetooth listener
,I/        ( 4910): StartBluetooth listener
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  880): discovery change broadcast true
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 4910): StartBroadcasting started ok
I/jxcore-log( 4910): 
I/jxcore-log( 4910): do fake peer & start
I/jxcore-log( 4910): 
I/jxcore-log( 4910): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:17.229Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:17.229Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:17.229Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/BTListenerThread( 4910): starting to listen
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/        ( 4910): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/BTConnectToThread( 4910): Starting to connect
,I/        ( 4910): Connecting to null, at F4:F1:E1:5C:3B:E2
,W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 4910): 2015-12-01T22:08:17.242Z SendDataTCPServer.js: TCP/IP server is bound to port: 52111
I/jxcore-log( 4910): 
,I/chromium( 4910): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
I/WB      ( 4910): We already were running, thus doing nothing
,I/        ( 4910): Added local service
I/        ( 4910): Cleared service requests
I/        ( 4910): Stopped peer discovery
I/        ( 4910): Started peer discovery
I/        ( 4910): Discovery state changed to Started.
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-52
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  880):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  880):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -52 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 1 peers.
I/SS      ( 4910): Peer(1): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  880):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  880):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6355, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6355, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9552, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9552, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
,E/bt-btif ( 4975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 4975): Entering PendingCommandState State
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34463c4a:true
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3fc354d8:true
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  880): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=6255 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6255): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1be5c497:true
,I/ActivityManager(  880): Killing 6013:android.process.acore/u0a7 (adj 15): empty #7
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 4975): Failed to remove device: F4:F1:E1:5C:3B:E2
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6013/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,D/BluetoothAdapterService( 4975): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@202359f
,D/BluetoothMetrics( 4975): btclass5a020c
,D/Checkin ( 4975): publish the event [tag = MOT_BT event name = PAIRING]
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
,W/bt-btif ( 4975): bta_dm_check_av:0
W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 4975): StableState(): Entering Off State
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef751c rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4910): Starting to Handshake
,I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4910): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 4910): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 4910): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4910): HandshakeOk : motorola-XT1039_PT3477
I/HS      ( 4910): Hand Shake finished outgoing for : motorola-XT1039_PT3477
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : false, motorola-XT1039_PT3477
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4910): mHTTPPort  set to : 58651
I/BtConnectorHelper( 4910): Request socket is using : 58651
I/BtToRequestSocket( 4910): Now accepting connections
,I/BtConnectorHelper( 4910): Calling ConnectionStatusUpdate with port :58651
,I/jxcore-log( 4910): 2015-12-01T22:08:23.678Z SendDataConnector.js: CLIENT connected to 58651, error: null
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:23.678Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): incoming data from: /127.0.0.1, port: 58651
I/BtToRequestSocket( 4910): Set local streams
I/BtToRequestSocket( 4910): rin ended ---------------------------;
,I/jxcore-log( 4910): 2015-12-01T22:08:23.694Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4910): 
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 4975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 4975): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,D/BluetoothMetrics( 4975): btclass5a020c
,I/BluetoothBondStateMachine( 4975): StableState(): Entering Off State
,D/Checkin ( 4975): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 4910): we got incoming connection
,I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/        ( 4975): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 4910): 2015-12-01T22:08:25.010Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:25.125Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/        ( 4975): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 4910): 2015-12-01T22:08:25.431Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:25.554Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/        ( 4975): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 4910): 2015-12-01T22:08:25.758Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:25.882Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:25.965Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:26.068Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4910): 
,I/BTListenerThread( 4910): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 4910): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
I/HS      ( 4910): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT371
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, samsung-SM-G900F_PT371
,I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BTConnectedThread
I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
I/jxcore-log( 4910): 2015-12-01T22:08:26.357Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
I/BtToRequestSocket( 4910): --DoOneRunRound ended
,I/jxcore-log( 4910): 2015-12-01T22:08:26.374Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 4910): 2015-12-01T22:08:27.398Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.404Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.406Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.410Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.413Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.416Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.436Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.473Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.480Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.513Z SendDataTCPServer.js: TCP/IP server has received 35912 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.522Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.558Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.592Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.599Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.606Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 4910): 
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=271, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309971, SEQNUM=4490, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-945, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/jxcore-log( 4910): 2015-12-01T22:08:27.655Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.668Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 4910): 
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,I/jxcore-log( 4910): 2015-12-01T22:08:27.703Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 4910): 
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,I/jxcore-log( 4910): 2015-12-01T22:08:27.743Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.781Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.790Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.794Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:27.882Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 4910): 
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=271, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310282, SEQNUM=4491, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-945, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/jxcore-log( 4910): 2015-12-01T22:08:27.930Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 4910): 
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ea:50:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
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
I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 fa
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-REQ 2437 fa
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 4975): dm_pm_timer expires
W/bt-btif ( 4975): dm_pm_timer expires 0
W/bt-btif ( 4975): proc dm_pm_timer expires
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 2 c0
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  880):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService(  880):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 b6
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-REQ 2437 b6
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP b6:ce:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/jxcore-log( 4910): 2015-12-01T22:08:36.357Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:36.358Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:36.360Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:36.363Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:36.365Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4910): 
,I/BtToSocketBase( 4910): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4910): Disconnect outgoing peer: motorola-XT1039_PT3477
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
,I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToRequestSocket( 4910): Close server socket
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 4975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 4975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 4975): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4975): StableState(): Entering Off State
,D/BluetoothMetrics( 4975): btclass5a020c
,D/Checkin ( 4975): publish the event [tag = MOT_BT event name = PAIRING]
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTListenerThread( 4910): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 4910): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
I/HS      ( 4910): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9087
I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9087
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BTConnectedThread
I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
,I/jxcore-log( 4910): 2015-12-01T22:08:37.054Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): --DoOneRunRound ended
,W/bt-btif ( 4975): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-49
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  880):  WFD CtrlPort: 7236
D/WifiP2pService(  880):  WFD MaxThroughput: 50
D/WifiP2pService(  880):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  880):  WFD CtrlPort: 7236
D/WifiP2pService(  880):  WFD MaxThroughput: 50
D/WifiP2pService(  880):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/jxcore-log( 4910): 2015-12-01T22:08:37.878Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:37.885Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:37.896Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:37.937Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.018Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.037Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.052Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 2 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.155Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.176Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.185Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.193Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 4910): 2015-12-01T22:08:38.279Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.311Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.315Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.329Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.337Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.371Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.502Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4910): 2015-12-01T22:08:38.790Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:38.946Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.043Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.081Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.085Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 4910): 
,W/bt-btif ( 4975): invalid rfc slot id: 4
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT371
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4910): 2015-12-01T22:08:39.103Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.353Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 4910): 
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.392Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.443Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.462Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.471Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.501Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.505Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.516Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.527Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.562Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.620Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4910): 2015-12-01T22:08:39.643Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.652Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.669Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 4910): 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-36
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-54
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: Android_50a5
D/WifiP2pService(  880):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService(  880):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4910): 2015-12-01T22:08:39.702Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 4910): 
D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/jxcore-log( 4910): 2015-12-01T22:08:39.751Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.781Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 4910): 
,W/bt-rfcomm( 4975): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 4975): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 4910): 2015-12-01T22:08:39.822Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.828Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:39.838Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 4910): 
,W/bt-btif ( 4975): invalid rfc slot id: 6
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9087
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
,I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9087
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Close bt socket
,I/jxcore-log( 4910): 2015-12-01T22:08:39.864Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:39.866Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef789c rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef751c rs_disc_pending=0
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 4975): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 4975): RFCOMM_DisconnectInd LCID:0x48
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP fa:cf:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP fa:cf:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8212, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8212, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:08:41.367Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:41.367Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=6330 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 23.280ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 23.940ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.911ms
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b56af8f:true
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6365 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 6330): Bluetooth Device Name: XT1039
,I/ActivityManager(  880): Killing 6107:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6107/cgroup.procs: No such file or directory
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef789c rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: HTC Desire 820
,I/art     (  880): Explicit concurrent mark sweep GC freed 25984(1731KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.510ms total 130.306ms
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
,D/TCMD    (  441): Listening for incoming client connection request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  880):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  880):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/jxcore-log( 4910): 2015-12-01T22:08:46.370Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:46.371Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:46.371Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:46.371Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 4910): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4910): Starting to Handshake
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4910): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTConnectToThread( 4910): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 4910): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4910): HandshakeOk : motorola-XT1039_PT3477
I/HS      ( 4910): Hand Shake finished outgoing for : motorola-XT1039_PT3477
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : false, motorola-XT1039_PT3477
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 4910): mHTTPPort  set to : 56687
I/BtConnectorHelper( 4910): Request socket is using : 56687
I/BtToRequestSocket( 4910): Now accepting connections
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 4910): Calling ConnectionStatusUpdate with port :56687
I/jxcore-log( 4910): 2015-12-01T22:08:47.796Z SendDataConnector.js: CLIENT connected to 56687, error: null
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:47.796Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): incoming data from: /127.0.0.1, port: 56687
I/BtToRequestSocket( 4910): Set local streams
I/BtToRequestSocket( 4910): rin ended ---------------------------;
,I/jxcore-log( 4910): 2015-12-01T22:08:47.810Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 4910): 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 3 
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Cleared service requests
,I/        ( 4910): Started peer discovery
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef751c rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 4 c0
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTListenerThread( 4910): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 4910): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
I/HS      ( 4910): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT371
I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, samsung-SM-G900F_PT371
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BTConnectedThread
I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/jxcore-log( 4910): 2015-12-01T22:08:49.599Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
,I/BtToRequestSocket( 4910): --DoOneRunRound ended
,I/jxcore-log( 4910): 2015-12-01T22:08:50.060Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:50.065Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:50.069Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:50.072Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:50.075Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:50.080Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4910): 
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  880):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  880):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 11 peers.
I/SS      ( 4910): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 4910): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4910): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4910): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4910): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4910): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4910): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4910): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4910): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4910): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 4910): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-REQ 2437 92
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  306): Event received = P2P: Reject scan trigger 
,I/        ( 4910): Started service discovery
,E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@268f8a52)
,E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34af1123)
,E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29d52620)
,E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e1f2bd9)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1577f99e)
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,W/bt-btif ( 4975): dm_pm_timer expires
,W/bt-btif ( 4975): dm_pm_timer expires 0
,W/bt-btif ( 4975): proc dm_pm_timer expires
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9552, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9552, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP b6:ce:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/ActivityManager(  880): Waited long enough for: ServiceRecord{212ea469 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/jxcore-log( 4910): 2015-12-01T22:08:57.876Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:57.877Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:08:57.877Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:57.878Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:08:57.878Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4910): 
,I/BtToSocketBase( 4910): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4910): Disconnect outgoing peer: motorola-XT1039_PT3477
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
I/BtToRequestSocket( 4910): Close server socket
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 4 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef751c rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4975): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ea:50:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4975): invalid rfc slot id: 7
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT371
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT371
I/BtToSocketBase( 4910): Close LocalOutputStream
,I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/jxcore-log( 4910): 2015-12-01T22:09:00.288Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 4975): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 4975): RFCOMM_DisconnectInd LCID:0x4d
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: XT1039
,I/jxcore-log( 4910): 2015-12-01T22:09:02.879Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:02.879Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 4910): 2015-12-01T22:09:07.881Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:07.881Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:07.882Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:07.882Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 4910): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 4910): Starting to connect
,W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4910): Cleared service requests
I/        ( 4910): Started peer discovery
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 12 peers.
I/SS      ( 4910): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 4910): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4910): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 4910): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4910): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4910): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4910): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 4910): Peer(8): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 4910): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4910): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4910): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 4910): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 3a:94:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP b6:ce:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ea:50:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9552, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9552, WifiDirectName: , WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-rfcomm( 4975): PORT_StartCnf failed result:5
,W/bt-btif ( 4975): invalid rfc slot id: 10
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4910): 2015-12-01T22:09:18.875Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:18.877Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:18.877Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: XT1039
,W/bt-btif ( 4975): info:x10
D/        ( 4975): remote version info [b0:c5:59:3f:75:69]: 6, 1d, 7d3
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
I/        ( 4910): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT8176, peerAddress: 34:FC:EF:11:AE:67
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT8176, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTListenerThread( 4910): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 4910): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
I/HS      ( 4910): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT371
I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, samsung-SM-G900F_PT371
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BTConnectedThread
,I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
I/BtToRequestSocket( 4910): --DoOneRunRound ended
,I/jxcore-log( 4910): 2015-12-01T22:09:19.524Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:20.040Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:20.082Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:20.090Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:20.403Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:20.408Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:20.568Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6355, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6355, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 4910): 2015-12-01T22:09:23.881Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:23.881Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/WifiP2pService(  880): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 4910): 2015-12-01T22:09:28.884Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:28.884Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:28.884Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:28.885Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 4910): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 4975): invalid rfc slot id: 9
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT371
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4910): 2015-12-01T22:09:30.147Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,W/bt-rfcomm( 4975): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 4975): RFCOMM_DisconnectInd LCID:0x42
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [f4:f1:e1:5c:3b:e2]: 7, f, 610c
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: XT1039
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef751c rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4910): Starting to Handshake
,I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4910): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Cleared service requests
I/        ( 4910): Started peer discovery
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef751c rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 4910): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 4910): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4910): HandshakeOk : motorola-XT1039_PT3477
I/HS      ( 4910): Hand Shake finished outgoing for : motorola-XT1039_PT3477
I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : false, motorola-XT1039_PT3477
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 4910): mHTTPPort  set to : 38009
I/BtConnectorHelper( 4910): Request socket is using : 38009
I/BtToRequestSocket( 4910): Now accepting connections
,I/BtConnectorHelper( 4910): Calling ConnectionStatusUpdate with port :38009
,I/jxcore-log( 4910): 2015-12-01T22:09:33.085Z SendDataConnector.js: CLIENT connected to 38009, error: null
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:33.085Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): incoming data from: /127.0.0.1, port: 38009
I/BtToRequestSocket( 4910): Set local streams
I/BtToRequestSocket( 4910): rin ended ---------------------------;
,I/jxcore-log( 4910): 2015-12-01T22:09:33.101Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 4910): 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  880):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  880):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 9 peers.
I/SS      ( 4910): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 4910): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4910): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4910): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4910): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4910): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 4910): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4910): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4910): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139301 arg2=22 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139310 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP b6:ce:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 4975): dm_pm_timer expires
,W/bt-btif ( 4975): dm_pm_timer expires 0
W/bt-btif ( 4975): proc dm_pm_timer expires
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT371, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT371, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/jxcore-log( 4910): 2015-12-01T22:09:43.159Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:43.160Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:43.160Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:43.161Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:43.161Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4910): 
,I/BtToSocketBase( 4910): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4910): Disconnect outgoing peer: motorola-XT1039_PT3477
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
,I/BtToSocketBase( 4910): Close LocalOutputStream
,I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4910): Close bt out
,I/BtToSocketBase( 4910): Close bt socket
I/BtToRequestSocket( 4910): Close server socket
,W/bt-btif ( 4975): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef751c rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTListenerThread( 4910): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 4910): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4910): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT371
I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, samsung-SM-G900F_PT371
,I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4910): Creating BTConnectedThread
I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
,I/jxcore-log( 4910): 2015-12-01T22:09:44.253Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): --DoOneRunRound ended
,I/jxcore-log( 4910): 2015-12-01T22:09:45.044Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:45.048Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:45.053Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:45.056Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:45.062Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:45.219Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: XT1039
,I/jxcore-log( 4910): 2015-12-01T22:09:48.162Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:48.162Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 4910): Cleared service requests
,I/        ( 4910): Started peer discovery
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 level=-43
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  880):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 33
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  880):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 33
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 10 peers.
I/SS      ( 4910): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 4910): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 4910): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4910): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4910): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 4910): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 4910): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 4910): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 4910): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4910): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=27 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139310 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
I/wpa_supplicant( 5020): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-51
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  880):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService(  880):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147477 obj=Device: Android_1950
D/WifiP2pService(  880):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  880):  WFD CtrlPort: 7236
D/WifiP2pService(  880):  WFD MaxThroughput: 50
D/WifiP2pService(  880):  level: -51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_1950
D/WifiP2pService(  880):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  880):  WFD CtrlPort: 7236
D/WifiP2pService(  880):  WFD MaxThroughput: 50
D/WifiP2pService(  880):  level: -51 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/jxcore-log( 4910): 2015-12-01T22:09:53.165Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:53.166Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:53.166Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:53.166Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 4910): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP b6:ce:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
,D/WifiP2pService(  880): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 3a:94:
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 7 
,D/WifiP2pService(  880): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,W/bt-sdp  ( 4975): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 14
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:09:59.910Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:59.911Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:59.921Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:09:59.922Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:59.923Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 4910): 
I/jxcore-log( 4910): ---- round done--------
I/jxcore-log( 4910): 
I/jxcore-log( 4910): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 4910): 
I/jxcore-log( 4910): do fake peer & start
I/jxcore-log( 4910): 
I/jxcore-log( 4910): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:59.925Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:59.926Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:09:59.926Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F8:CF:C5:D9:E5:61, name: null
,I/        ( 4910): Connecting to null, at F8:CF:C5:D9:E5:61
I/chromium( 4910): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: Connection to F4:F1:E1:5C:3B:E2 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=0
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4975): invalid rfc slot id: 11
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT371
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4910): 2015-12-01T22:10:00.192Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7a5c rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 4975): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 4975): RFCOMM_DisconnectInd LCID:0x47
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,E/bt-btif ( 4975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 4975): Entering PendingCommandState State
,I/ActivityManager(  880): Killing 6145:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10005/pid_6145/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 4975): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4975): StableState(): Entering Off State
,D/BluetoothMetrics( 4975): btclass5a020c
,D/Checkin ( 4975): publish the event [tag = MOT_BT event name = PAIRING]
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7a5c rs_disc_pending=0
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT371, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT371, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7a5c rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:1
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4910): Starting to Handshake
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTConnectToThread( 4910): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,E/bt-btm  ( 4975): peer should have initiated security process by now (SM4 to SM4)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef76dc rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 4910): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4910): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 4910): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 4910): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4910): HandshakeOk : motorola-Nexus 6_PT8212
I/HS      ( 4910): Hand Shake finished outgoing for : motorola-Nexus 6_PT8212
I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
I/HS      ( 4910): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT8212
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : false, motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BtConnectedRequestSocket
I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BTConnectedThread
I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/BtToRequestSocket( 4910): mHTTPPort  set to : 51456
I/BtConnectorHelper( 4910): Request socket is using : 51456
I/BtToRequestSocket( 4910): Now accepting connections
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
I/BtToRequestSocket( 4910): --DoOneRunRound ended
,I/jxcore-log( 4910): 2015-12-01T22:10:08.530Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,I/BtConnectorHelper( 4910): Calling ConnectionStatusUpdate with port :51456
,I/jxcore-log( 4910): 2015-12-01T22:10:08.825Z SendDataConnector.js: CLIENT connected to 51456, error: null
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:10:08.825Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): incoming data from: /127.0.0.1, port: 51456
I/BtToRequestSocket( 4910): Set local streams
I/BtToRequestSocket( 4910): rin ended ---------------------------;
,I/jxcore-log( 4910): 2015-12-01T22:10:08.840Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7a5c rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 4975): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8600
,I/jxcore-log( 4910): 2015-12-01T22:10:09.425Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:09.441Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:09.521Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:09.527Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 4975): L2CAP got sec_comp for unknown BD_ADDR
,D/BluetoothMapService( 4975): onReceive
,I/jxcore-log( 4910): 2015-12-01T22:10:09.575Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:09.583Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 4910): 
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 4910): 2015-12-01T22:10:09.654Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:09.719Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:09.817Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:09.856Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:09.902Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.033Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.039Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.090Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.122Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.166Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.172Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 4910): 
,D/        ( 4975): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19038
,I/jxcore-log( 4910): 2015-12-01T22:10:10.243Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.330Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.339Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.391Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.565Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.702Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.782Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:10.790Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 4910): 
,D/        ( 4975): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9138
,I/jxcore-log( 4910): 2015-12-01T22:10:10.882Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.020Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.052Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.077Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.081Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.098Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.186Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.194Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.200Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.217Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.226Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.231Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.315Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.351Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 4910): 2015-12-01T22:10:11.405Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.411Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.462Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.529Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.630Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.662Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.702Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.741Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.763Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:11.968Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.002Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.056Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.092Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.102Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.131Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.158Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.238Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.271Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.292Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:12.313Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 4910): 
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Cleared service requests
,I/        ( 4910): Started peer discovery
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 8 c0
D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 8 
,W/bt-btif ( 4975): dm_pm_timer expires
,W/bt-btif ( 4975): dm_pm_timer expires 0
W/bt-btif ( 4975): proc dm_pm_timer expires
,I/ActivityManager(  880): Waited long enough for: ServiceRecord{5ab0187 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:10:22.292Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:10:22.293Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:10:22.293Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:10:22.294Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:10:22.294Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4910): 
,I/BtToSocketBase( 4910): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4910): Disconnect outgoing peer: motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
,I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
I/BtToRequestSocket( 4910): Close server socket
,W/bt-btif ( 4975): invalid rfc slot id: 13
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4910): 2015-12-01T22:10:22.568Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,W/bt-btif ( 4975): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 4910): 2015-12-01T22:10:27.295Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:27.295Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 5 peers.
I/SS      ( 4910): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 4910): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 4910): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4910): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 4910): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=32 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139310 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-49
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 c0
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 9 c0
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  880):  WFD CtrlPort: 7236
D/WifiP2pService(  880):  WFD MaxThroughput: 50
D/WifiP2pService(  880):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  880):  WFD CtrlPort: 7236
D/WifiP2pService(  880):  WFD MaxThroughput: 50
D/WifiP2pService(  880):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP b6:ce:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT371, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT371, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 3a:94:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:10:32.298Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:10:32.298Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:10:32.298Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:10:32.298Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 4910): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 610c
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7a5c rs_disc_pending=0
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 9 
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Cleared service requests
,I/        ( 4910): Started peer discovery
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 c
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 10 c
D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 10
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 10
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=3a:94:96
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=3a:94:96
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 2 peers.
I/SS      ( 4910): Peer(1): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4910): Peer(2): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032 vendor_elems=1 level=-48
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 11 c
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 11 c
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  880):  WFD CtrlPort: 7236
D/WifiP2pService(  880):  WFD MaxThroughput: 50
D/WifiP2pService(  880):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService(  880):  WFD CtrlPort: 7236
D/WifiP2pService(  880):  WFD MaxThroughput: 50
D/WifiP2pService(  880):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-rfcomm( 4975): PORT_StartCnf failed result:5
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 4975): invalid rfc slot id: 17
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Nexus 6
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 4910): 2015-12-01T22:11:06.521Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:06.521Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:06.522Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 11
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 11
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Cleared service requests
,I/        ( 4910): Started peer discovery
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 12 c
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 12 c
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 4 peers.
I/SS      ( 4910): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4910): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 4910): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 4910): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=47 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=47 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:11:11.523Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:11.523Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139310 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 4910): 2015-12-01T22:11:16.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:16.525Z SendDataConnector.js: Connect (retry count 2) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:16.526Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:16.526Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 4910): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 4975): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 18
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:11:18.080Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:18.080Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:18.081Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 12
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 12
,I/MDMCTBK (  306): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  306): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  306): checkDefaultInst, current pid is = 306
I/MDMCTBK (  306): checkDefaultInst, pid match
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  306): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  306): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311490, SEQNUM=4536, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1040, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 4975): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Cleared service requests
,I/        ( 4910): Started peer discovery
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 13 c
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 13 c
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  880):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  880):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 4488
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 5 peers.
,I/SS      ( 4910): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 4910): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 4910): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 4910): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 4910): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 4910): Added service request
,I/jxcore-log( 4910): 2015-12-01T22:11:23.081Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:23.081Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
,I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
,D/TCMD    (  441): Listening for incoming client connection request
,I/BTListenerThread( 4910): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4910): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4910): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT8212
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BTConnectedThread
I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
,I/BtToRequestSocket( 4910): --DoOneRunRound ended
,I/jxcore-log( 4910): 2015-12-01T22:11:24.661Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:25.071Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:25.076Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:25.082Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:25.086Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:25.126Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:25.130Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT371","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT371, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT371, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 4910): 2015-12-01T22:11:28.083Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:28.084Z SendDataConnector.js: Connect (retry count 3) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:28.084Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:28.084Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 4910): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4910): Starting to Handshake
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4910): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTConnectToThread( 4910): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 4910): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4910): HandshakeOk : motorola-Nexus 6_PT8212
I/HS      ( 4910): Hand Shake finished outgoing for : motorola-Nexus 6_PT8212
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : false, motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 4910): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 4910): mHTTPPort  set to : 41268
I/BtConnectorHelper( 4910): Request socket is using : 41268
I/BtToRequestSocket( 4910): Now accepting connections
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 13
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 13
,I/BtConnectorHelper( 4910): Calling ConnectionStatusUpdate with port :41268
,I/jxcore-log( 4910): 2015-12-01T22:11:28.588Z SendDataConnector.js: CLIENT connected to 41268, error: null
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:28.588Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): incoming data from: /127.0.0.1, port: 41268
,I/BtToRequestSocket( 4910): Set local streams
,I/BtToRequestSocket( 4910): rin ended ---------------------------;
,I/jxcore-log( 4910): 2015-12-01T22:11:28.610Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 4910): 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4975): invalid rfc slot id: 16
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4910): 2015-12-01T22:11:35.355Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139265 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Cleared service requests
,I/        ( 4910): Started peer discovery
,I/jxcore-log( 4910): 2015-12-01T22:11:38.669Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:38.669Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:38.670Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:38.670Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:38.674Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 4910): 
,I/BtToSocketBase( 4910): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 4910): Disconnect outgoing peer: motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
I/BtToRequestSocket( 4910): Close server socket
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 14 c
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 14 c
D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,W/bt-btif ( 4975): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:11:43.674Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:43.674Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Nexus 6
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 14
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 14
,I/jxcore-log( 4910): 2015-12-01T22:11:48.677Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:48.678Z SendDataConnector.js: Connect (retry count 4) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:48.678Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:48.678Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 4910): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 4975): SDP - Rcvd conn cnf with error: 0xc  CID 0x44
E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 21
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:11:48.706Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:48.706Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:48.712Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:48.712Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:48.715Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 4910): 
I/jxcore-log( 4910): ---- round done--------
I/jxcore-log( 4910): 
I/jxcore-log( 4910): ---- gotta redo : F8:CF:C5:D9:E5:61, try count now: 1
I/jxcore-log( 4910): 
I/jxcore-log( 4910): do fake peer & start
I/jxcore-log( 4910): 
I/jxcore-log( 4910): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:48.716Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:48.716Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:48.716Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 4910): Connecting to null, at 58:3F:54:73:64:C0
I/chromium( 4910): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: Connection to F8:CF:C5:D9:E5:61 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,W/bt-sdp  ( 4975): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 22
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:11:58.983Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:11:58.983Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:11:58.984Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:12:03.985Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:03.985Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
,I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTListenerThread( 4910): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 4910): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
I/HS      ( 4910): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT8212
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BTConnectedThread
,I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
,I/jxcore-log( 4910): 2015-12-01T22:12:06.753Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): --DoOneRunRound ended
,I/jxcore-log( 4910): 2015-12-01T22:12:07.168Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:07.173Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:07.179Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:07.221Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:07.225Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:07.231Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:08.987Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:08.987Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:08.988Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:08.988Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 4910): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7a5c rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 24
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:12:10.292Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:10.292Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:10.293Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 4910): 2015-12-01T22:12:15.294Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:15.294Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,W/bt-btif ( 4975): invalid rfc slot id: 19
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT8212
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 4910): 2015-12-01T22:12:17.439Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,W/bt-rfcomm( 4975): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 4975): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 4910): 2015-12-01T22:12:20.296Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:20.296Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:20.296Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:20.296Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 4910): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Nexus 6
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 5020): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  306): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=-18ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-18ms what=147478 obj=Device: 
D/WifiP2pService(  880):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  880):  primary type: null
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 0
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 0
D/WifiP2pService(  880):  status: 4
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): We got empty peers list
I/SS      ( 4910): We got empty peers list
I/SS      ( 4910): We got empty peers list
I/SS      ( 4910): We got empty peers list
,I/SS      ( 4910): We got empty peers list
,W/bt-sdp  ( 4975): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 25
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:12:30.566Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:30.567Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:30.567Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:12:35.568Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:35.569Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:40.573Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:40.573Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:40.573Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:40.573Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 4910): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,W/bt-sdp  ( 4975): SDP - Rcvd conn cnf with error: 0xd  CID 0x4c
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 26
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:12:50.850Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:50.853Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:12:50.853Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:12:55.855Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:12:55.855Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 4910): 2015-12-01T22:13:00.857Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:00.857Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:00.857Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:00.857Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 4910): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 4975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 4975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 4975): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4975): StableState(): Entering Off State
,D/BluetoothMetrics( 4975): btclass5a020c
,D/Checkin ( 4975): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTListenerThread( 4910): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 4910): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 4910): MESSAGE_WRITE 81 bytes.
,I/HS      ( 4910): Incoming connection Hand Shake finished for : LGE-LG-D802_PT384
I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : true, LGE-LG-D802_PT384
,I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BTConnectedThread
,I/BtConnectorHelper( 4910): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 4910): --DoOneRunRound started
,I/BtToRequestSocket( 4910): LocalHost address: localhost/127.0.0.1, port: 52111
I/BtToRequestSocket( 4910): --DoOneRunRound ended
,I/jxcore-log( 4910): 2015-12-01T22:13:01.242Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 4910): 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 4910): 2015-12-01T22:13:02.230Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.236Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.241Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.244Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.277Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.320Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.328Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.362Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.366Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.370Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.377Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.411Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.491Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.520Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.548Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.582Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.623Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.658Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.687Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.716Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.751Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.792Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.832Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.859Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.917Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.951Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:02.992Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.004Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.090Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.122Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.162Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.228Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.243Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.288Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.364Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.402Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.441Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.448Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.481Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.545Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.582Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.602Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.664Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.702Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:03.742Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 4910): 
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 27
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:13:11.239Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:11.239Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:11.247Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:11.249Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 4910): 
I/jxcore-log( 4910): ---- round done--------
I/jxcore-log( 4910): 
I/jxcore-log( 4910): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 4910): 
I/jxcore-log( 4910): do fake peer & start
I/jxcore-log( 4910): 
I/jxcore-log( 4910): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:11.250Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:11.250Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:11.250Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 4910): Connecting to null, at E0:DB:10:1F:C9:5E
,I/chromium( 4910): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: Connection to 58:3F:54:73:64:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4975): invalid rfc slot id: 23
,I/BtToSocketBase( 4910): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT384
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 4910): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT384
I/BtToSocketBase( 4910): Close bt in
I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
,I/jxcore-log( 4910): 2015-12-01T22:13:14.296Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 4910): 
,W/bt-rfcomm( 4975): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 4975): RFCOMM_DisconnectInd LCID:0x4d
,W/bt-btm  ( 4975): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7c1c rs_disc_pending=2
E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Thali Test's G2
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 4975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 4975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 4975): Failed to remove device: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4975): StableState(): Entering Off State
,D/BluetoothMetrics( 4975): btclass5a020c
,D/Checkin ( 4975): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 4910): Starting to Handshake
,I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 4910): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/BTConnectToThread( 4910): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 4910): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 4910): HandshakeOk : samsung-SM-N9005_PT2504
I/HS      ( 4910): Hand Shake finished outgoing for : samsung-SM-N9005_PT2504
,I/BtConnectorHelper( 4910): Starting the connected thread incoming : false, samsung-SM-N9005_PT2504
,I/BtToSocketBase( 4910): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 4910): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 4910): mHTTPPort  set to : 48864
I/BtConnectorHelper( 4910): Request socket is using : 48864
I/BtToRequestSocket( 4910): Now accepting connections
,I/BtConnectorHelper( 4910): Calling ConnectionStatusUpdate with port :48864
,I/jxcore-log( 4910): 2015-12-01T22:13:22.848Z SendDataConnector.js: CLIENT connected to 48864, error: null
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:22.848Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 4910): 
,I/BtToRequestSocket( 4910): incoming data from: /127.0.0.1, port: 48864
,I/BtToRequestSocket( 4910): Set local streams
I/BtToRequestSocket( 4910): rin ended ---------------------------;
,I/jxcore-log( 4910): 2015-12-01T22:13:22.862Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.361Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.438Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.441Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.463Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.517Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.529Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.588Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.686Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.741Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7f9c rs_disc_pending=0
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 4910): 2015-12-01T22:13:23.935Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.936Z SendDataConnector.js: got all data for this round
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.944Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:23.944Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 4910): 
I/BtConnectorHelper( 4910): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 4910): Stop ReceivingThread
I/BtToSocketBase( 4910): Stop SendingThread
I/BtToSocketBase( 4910): Close local in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 4910): Close LocalOutputStream
I/BtToSocketBase( 4910): Close localHostSocket
I/BtToSocketBase( 4910): Close bt in
,I/BtToSocketBase( 4910): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 4910): Close bt out
I/BtToSocketBase( 4910): Close bt socket
I/BtToRequestSocket( 4910): Close server socket
,I/jxcore-log( 4910): 2015-12-01T22:13:23.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 4910): 
I/jxcore-log( 4910): ---- round done--------
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): do fake peer & start
I/jxcore-log( 4910): 
I/jxcore-log( 4910): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:23.962Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:23.962Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:23.962Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: 34:FC:EF:11:B1:66, name: null
,W/bt-btif ( 4975): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/        ( 4910): Connecting to null, at 34:FC:EF:11:B1:66
,I/chromium( 4910): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7f9c rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef831c rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef7f9c rs_disc_pending=0
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 30
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:13:25.584Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:25.584Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:25.584Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 4975): onReceive
,I/BTConnectionReceiver( 6330): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6330): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 4910): 2015-12-01T22:13:30.585Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:30.585Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
,D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  880): Waited long enough for: ServiceRecord{b58ecdd u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/jxcore-log( 4910): 2015-12-01T22:13:35.587Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:35.588Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:35.588Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:35.588Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 4910): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 5020): P2P-FIND-STOPPED 
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  306): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): discovery change broadcast false
,D/WifiP2pService(  880): InactiveState{ when=0 what=139265 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139265 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  880): discovery change broadcast true
,I/        ( 4910): Discovery state changed to Stopped.
,I/        ( 4910): Started peer discovery
I/        ( 4910): Discovery state changed to Started.
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-30
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 15 c
D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 15 c
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 1 peers.
I/SS      ( 4910): Peer(1): Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=64 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=64 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 4910): Added service request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139310 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,I/wpa_supplicant( 5020): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  306): Event received = P2P: Reject scan trigger 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-35
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  880):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  880):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 33
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: XT1039_8c05
D/WifiP2pService(  880):  deviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 33
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP f4:f1:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP f4:f1:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 4910): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,W/bt-sdp  ( 4975): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 31
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:13:45.861Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:45.863Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:45.864Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 02
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-REQ 2437 02
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
,D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 15
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 15
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 16 c
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-ADDED 16 c
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService(  880):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/jxcore-log( 4910): 2015-12-01T22:13:50.864Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:50.865Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 4910): 2015-12-01T22:13:55.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
,I/jxcore-log( 4910): 2015-12-01T22:13:55.867Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:55.867Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:55.867Z SendDataConnector.js: do connect now
I/jxcore-log( 4910): 
,I/        ( 4910): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 4910): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 4910): Starting to connect
W/BluetoothAdapter( 4910): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 4975): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/WifiP2pService(  880): InactiveState{ when=0 what=139307 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139307 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState clear service request
,D/WifiP2pService(  880): InactiveState{ when=-1ms what=139265 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=139265 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5020): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  306): Event received = P2P: Reject scan trigger 
,I/        ( 4910): Cleared service requests
,I/        ( 4910): Started peer discovery
,I/wpa_supplicant( 5020): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  306): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  306): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  880): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  880):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  880):  primary type: 10-0050F204-5
D/WifiP2pService(  880):  secondary type: null
D/WifiP2pService(  880):  wps: 392
D/WifiP2pService(  880):  grpcapab: 0
D/WifiP2pService(  880):  devcapab: 37
D/WifiP2pService(  880):  status: 3
D/WifiP2pService(  880):  wfdInfo: null
D/WifiP2pService(  880):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
,D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): DefaultState{ when=0 what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 4910): Found 4 peers.
I/SS      ( 4910): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 4910): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 4910): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 4910): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pService(  880): InactiveState{ when=0 what=139301 arg2=69 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139301 arg2=69 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState add service request
,D/WifiP2pManager( 4910): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 4910): Added service request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/WifiP2pService(  880): InactiveState{ when=0 what=139310 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=139310 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState discover services
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,I/        ( 4910): Started service discovery
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,I/wpa_supplicant( 5020): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP f4:f1:
D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP f4:f1:
D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  306): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:f4:f1:e1:5c:43:c8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT3477, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT3477, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [00:f4:6f:30:e0:6c]: 7, f, 6109
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,D/TCMD    (  441): NL - Read 56 bytes from update socket.
,D/TCMD    (  441): NL - message type is RTM_NEWLINK
D/TCMD    (  441): Listening for incoming client connection request
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 16
,D/MDMCTBK (  306): Event received = CTRL-EVENT-BSS-REMOVED 16
,W/bt-btif ( 4975): info:x10
,D/        ( 4975): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  306): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  306): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService(  880): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState receive service response
,I/        ( 4910): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 4910): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 4910): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,E/bt-btif ( 4975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 4975): Entering PendingCommandState State
,W/bt-sdp  ( 4975): process_service_search_attr_rsp
,E/bt-btif ( 4975): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 4975): invalid rfc slot id: 32
,I/BTConnectToThread( 4910): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 4910): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 4910): 2015-12-01T22:13:59.700Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:59.700Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 4910): 
I/jxcore-log( 4910): 2015-12-01T22:13:59.700Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 4910): 
,I/BluetoothBondStateMachine( 4975): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 4975): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 4975): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 4975): StableState(): Entering Off State
,D/BluetoothMetrics( 4975): btclass5a020c
,D/Checkin ( 4975): publish the event [tag = MOT_BT event name = PAIRING]
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef815c rs_disc_pending=1
,W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef831c rs_disc_pending=1
W/bt-btif ( 4975): bta_dm_check_av:0
,W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 4975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 4975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 4975): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 4910): we got incoming connection
,I/BTHandshakeSocketThread( 4910): Creating BTHandshakeSocketThread
,I/BTListenerThread( 4910): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 4910): BTHandshakeSocketThread started
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 600000ms),D/AndroidRuntime( 6693): 
D/AndroidRuntime( 6693): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6693): CheckJNI is OFF
W/bt-btm  ( 4975): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 4975): tBTM_SEC_DEV:0xa6ef831c rs_disc_pending=2
E/bt-btm  ( 4975): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 4975): bta_dm_check_av:0
W/bt-btif ( 4975): btif_dm_cback : unhandled event (14)
E/BluetoothRemoteDevices( 4975): aclStateChangeCallback: Device is NULL
D/AndroidRuntime( 6693): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 4910:com.test.thalitest/u0a338 (adj 9): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{13a978a4 com.example.hello/10333} due to missing metadata
I/WindowState(  880): WIN DEATH: Window{3e2b225b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
I/ActivityManager(  880):   Force finishing activity ActivityRecord{139e6e44 u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  880): Spurious death for ProcessRecord{17ac2f23 4910:com.test.thalitest/u0a338}, curProc for 4910: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
I/ActivityManager(  880):   Force finishing activity ActivityRecord{139e6e44 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{139e6e44 u0 com.test.thalitest/.MainActivity t3 f}
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1407): resetDictionaries() : en_US
W/GeofencerStateMachine( 1709): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1407): run()
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6713 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 2983): Explicit concurrent mark sweep GC freed 19087(2MB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 7MB/12MB, paused 4.102ms total 99.901ms
I/art     ( 1556): Explicit concurrent mark sweep GC freed 7678(548KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 485us total 115.788ms
I/Decoder ( 1407): createOrResetDecoder
D/btif_config_util( 4975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/ConfigService( 1601): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): run()
I/art     (  880): Explicit concurrent mark sweep GC freed 42354(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.879ms total 197.009ms
I/art     (  880): WaitForGcToComplete blocked for 67.901ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1407): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1407): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1407): run()
I/StatsUtilsManager( 1407): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1407): shouldRecordStats() = Too Soon
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/art     (  880): Explicit concurrent mark sweep GC freed 6532(331KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 4.162ms total 135.966ms
I/Launcher( 1556): Deferring update until onResume
I/art     (  880): WaitForGcToComplete blocked for 261.591ms for cause Explicit
D/VoicemailCleanupService( 6713): Cleaning up data for package: com.test.thalitest
I/ContactLocale( 6713): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6747 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  880): Explicit concurrent mark sweep GC freed 3235(180KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.594ms total 122.191ms
I/ActivityManager(  880): Killing 1943:com.google.android.gms/u0a16 (adj 15): empty #7
D/WifiService(  880): Client connection lost with reason: 4
D/ConnectivityService(  880): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@225727a4)
D/ConnectivityService(  880): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  880): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_1943/cgroup.procs: No such file or directory
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
W/asset   ( 6747): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6747): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6747): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6747): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
D/AndroidRuntime( 6693): Shutting down VM
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6767 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/ContextImpl( 6767): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6794 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 5329:com.google.android.calendar/u0a49 (adj 15): empty #7
W/libprocessgroup(  880): failed to open /acct/uid_10049/pid_5329/cgroup.procs: No such file or directory
I/ActivityManager(  880): Killing 6365:com.google.android.partnersetup/u0a19 (adj 15): empty #7
W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_6365/cgroup.procs: No such file or directory
D/Finsky  ( 6794): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
