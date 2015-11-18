#### Test 5105326192ae435_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1015): sending alarm Alarm{43f417d8 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3511): 
D/AndroidRuntime( 3511): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3511): CheckJNI is OFF
D/dalvikvm( 3511): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3511): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3511): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3511): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3511): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3511): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3511): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3511): failed to load memtrack module: -2
D/AndroidRuntime( 3511): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3511
W/WindowManager( 1015): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3527 uid=10380 gids={50380, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3511): Shutting down VM
D/dalvikvm( 3511): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+4ms, total 26ms
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
V/WebViewChromiumFactoryProvider( 3527): Binding Chromium to main looper Looper (main, tid 1) {420a28e0}
I/LibraryLoader( 3527): Expected native library version number "",actual native library version number ""
I/chromium( 3527): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3527): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@433d5678:true
D/BluetoothAdapter( 3527): 1108045552: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3527): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3527): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3527): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3527): Local Branch: 
I/Adreno-EGL( 3527): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3527): Local Patches: NONE
I/Adreno-EGL( 3527): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3527): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3527): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3527): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3527): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3527): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3527): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3527): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3527): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3527): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3527): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3527): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3527): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3527): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 3527): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3527): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3527): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3527): Enabling debug mode 0
,W/AwContents( 3527): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1015): Displayed com.test.thalitest/.MainActivity,cp,ca,391
I/ActivityManager( 1015): Displayed com.test.thalitest/.MainActivity: +362ms (total +391ms)
W/AwContents( 3527): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3527): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3527): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3527): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x420a6d90
,D/dalvikvm( 3527): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x420a6d90
,D/jxcore_app_log( 3527): JniHelper::setJavaVM(0x417bbf78), pthread_self() = 1615123040
,D/JX-Cordova( 3527): jxcore cordova android initializing
,I/dalvikvm( 3527): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 3527): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3527): GC_CONCURRENT freed 2789K, 17% free 14377K/17224K, paused 3ms+2ms, total 43ms
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 227K, 17% free 14362K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 183K, 17% free 14394K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3527): Grow heap (frag case) to 16.229MB for 146998-byte allocation
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 263K, 17% free 14435K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3527): Grow heap (frag case) to 16.339MB for 220492-byte allocation
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 374K, 18% free 14511K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3527): Grow heap (frag case) to 16.519MB for 330734-byte allocation
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 580K, 19% free 14635K/17908K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3527): Grow heap (frag case) to 16.798MB for 496096-byte allocation
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 879K, 20% free 14813K/18396K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3527): Grow heap (frag case) to 17.208MB for 744140-byte allocation
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 1302K, 22% free 15075K/19124K, paused 27ms, total 27ms
,D/dalvikvm( 3527): GC_CONCURRENT freed 1672K, 20% free 15450K/19124K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 3527): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 408K, 20% free 15414K/19124K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3527): Grow heap (frag case) to 18.682MB for 1674304-byte allocation
,D/dalvikvm( 3527): GC_CONCURRENT freed 1695K, 24% free 15983K/20760K, paused 1ms+3ms, total 33ms
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 1406K, 23% free 16076K/20760K, paused 30ms, total 33ms
,I/dalvikvm-heap( 3527): Grow heap (frag case) to 20.127MB for 2511452-byte allocation
,D/dalvikvm( 3527): GC_CONCURRENT freed 265K, 21% free 18383K/23216K, paused 4ms+4ms, total 34ms
,D/dalvikvm( 3527): GC_CONCURRENT freed 4394K, 27% free 17060K/23216K, paused 2ms+7ms, total 41ms
,D/dalvikvm( 3527): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/dalvikvm-heap( 3527): Grow heap (frag case) to 22.286MB for 3767174-byte allocation
,D/dalvikvm( 3527): GC_CONCURRENT freed 305K, 24% free 20666K/26896K, paused 5ms+5ms, total 54ms
,D/dalvikvm( 3527): GC_FOR_ALLOC freed 3049K, 34% free 18001K/26896K, paused 28ms, total 28ms
,W/jxcore-log( 3527): Initializing JXcore engine
,W/jxcore-log( 3527): JXcore engine is ready
,W/jxcore-log( 3527): Starting JXcore engine
,D/dalvikvm( 3527): GC_CONCURRENT freed 307K, 24% free 20679K/26896K, paused 1ms+2ms, total 32ms
,W/jxcore-log( 3527): Platform android
W/jxcore-log( 3527): 
,W/jxcore-log( 3527): Process ARCH arm
W/jxcore-log( 3527): 
,I/jxcore-log( 3527): JXcore Cordova bridge is ready!
I/jxcore-log( 3527): 
,W/jxcore-log( 3527): JXcore engine is started
,I/chromium( 3527): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3527): Turning radios to true
I/jxcore-log( 3527): 
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1015): Message: 1
,D/BluetoothManagerService( 1015): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): New client listening to asynchronous messages
D/WifiService( 1015): setWifiEnabled: true pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
I/ActivityManager( 1015): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3573 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
D/WifiStateMachine( 1015): setting operational mode to 1
D/WifiStateMachine( 1015): handleMessage: E msg.what=131083
D/WifiStateMachine( 1015): processMsg: InitialState
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
,W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/AdapterServiceConfig( 3573): Adding HeadsetService
D/AdapterServiceConfig( 3573): Adding A2dpService
D/AdapterServiceConfig( 3573): Adding HidService
D/AdapterServiceConfig( 3573): Adding HealthService
D/AdapterServiceConfig( 3573): Adding PanService
D/AdapterServiceConfig( 3573): Adding GattService
,D/AdapterServiceConfig( 3573): Adding BluetoothMapService
,D/BluetoothAdapterService( 3573): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothManagerService( 1015): Message: 20
D/BluetoothAdapterState( 3573): make
,D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e437d0:true
I/bluedroid( 3573): init
,I/BluetoothAdapterState( 3573): Entering OffState
,I/bte_conf( 3573): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bluedroid( 3573): get_profile_interface socket
,I/GKI_LINUX( 3573): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService( 1015): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1015): Message: 40
,D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3573): config_hci_snoop_log
D/BluetoothManagerService( 1015): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterState( 3573): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3573): Setting state to 11
I/BluetoothAdapterState( 3573): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3573): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1015): Message: 60
,D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothBondStateMachine( 3573): make
,D/BluetoothAdapterProperties( 3573): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:1 len:6
,I/ActivityManager( 1015): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3602 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/BluetoothBondStateMachine( 3573): StableState(): Entering Off State
,D/BluetoothHeadset( 1015): Proxy object connected
,D/HeadsetService( 3573): Received start request. Starting profile...
,D/BluetoothHeadset( 1243): Proxy object connected
D/BluetoothHeadset( 1243): Proxy object connected
,D/BluetoothHeadset( 1243): Proxy object connected
I/BluetoothHeadsetServiceJni( 3573): classInitNative: succeeds
D/HeadsetStateMachine( 3573): Version 1.6
,D/HeadsetStateMachine( 3573): make
,D/BluetoothAdapterProperties( 3573): Name is: XT1039
,D/BluetoothManagerService( 1015): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1015): Stored Bluetooth name: XT1039
,I/BluetoothAdapterState( 3573): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3573): get_profile_interface handsfree
,D/BluetoothA2dp( 1015): Proxy object connected
,D/A2dpService( 3573): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3573): classInitNative: succeeds
V/Avrcp   ( 3573): make
,I/bluedroid( 3573): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3573): classInitNative: succeeds
,D/A2dpStateMachine( 3573): make
,I/bluedroid( 3573): get_profile_interface a2dp
,I/GKI_LINUX( 3573): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3573): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3573): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3573): classInitNative: succeeds
,D/HidService( 3573): Received start request. Starting profile...
I/bluedroid( 3573): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3573): classInitNative: succeeds
,D/HealthService( 3573): Received start request. Starting profile...
,I/bluedroid( 3573): get_profile_interface health
,I/BluetoothPanServiceJni( 3573): classInitNative(L105): succeeds
,D/BluetoothPan( 1015): BluetoothPAN Proxy object connected
D/PanService( 3573): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3573): initializeNative(L110): pan
,I/bluedroid( 3573): get_profile_interface pan
D/BluetoothTethering( 1015): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1015): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43e09ba8
,I/BtGatt.JNI( 3573): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3573): handleDebugAction() action=null
D/BtGatt.GattService( 3573): Received start request. Starting profile...
D/BtGatt.GattService( 3573): start()
,I/bluedroid( 3573): get_profile_interface gatt
,I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  274): NetlinkHandler, interfaceAdded
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
E/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  274): , Wifi = 0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/BluetoothMapService( 3573): Received start request. Starting profile...
,D/BluetoothMapService( 3573): start()
,D/HeadsetPhoneState( 3573): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/Tethering( 1015): InitialState.processMessage what=4
,D/HeadsetPhoneState( 3573): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3573): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3573): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3573): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3573): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3573): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3573): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3573): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3573): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3573): enable
D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  274): NetlinkHandler, interfaceAdded
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
E/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  274): , Wifi = 0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/bt_hci_bdroid( 3573): init
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/bt_vendor( 3573): bt-vendor : init
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/bt_hci_bdroid( 3573): ro.qualcomm.hci_transport set to smd
,D/bt_userial_mct( 3573): userial_init
D/TCMD    (  480): NL - Read 1004 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
I/bt_hwcfg( 3573): Starting hciattach daemon
,I/bt_hwcfg( 3573): try to set false
I/bt_hwcfg( 3573): Starting hciattach daemon
,I/bt_hwcfg( 3573): try to set true
,I/bt_hci_bdroid( 3573): bt_hc_worker_thread started
D/QsoftapCmd(  272): Got softap fwreload command we are passing on
,D/SoftapController(  272): Softap fwReload - Ok
,D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring down wlan0
,I/qcom-bluetooth( 3636): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager( 1015): Killing 3356:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/qcom-bluetooth( 3644): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3645): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/WifiService( 1015): New client listening to asynchronous messages
,I/qcom-bluetooth( 3648): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3649): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3650): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,V/BluetoothFtpReceiver( 3573): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1333): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/Diag_Lib( 3652): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3652): Setting internal use port to rmnet0
E/Diag_Lib( 3652):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
E/Diag_Lib( 3652): Failed on DIAG init
E/Diag_Lib( 3652): linux_qmi_qmux_if_client_get_proc_name: pid=3652, proc_name=hci_qcomm_init
E/Diag_Lib( 3652): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3652): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3652): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
,E/Diag_Lib( 3652): qmi_client [3652]: successfully connected to server, attempt=1
E/Diag_Lib( 3652): linux_qmi_qmux_if_client_get_client_id [3652]: qmux_client_id=13
E/Diag_Lib( 3652): qmi_client [3652] 13: qmux_client ID is initialized
E/Diag_Lib( 3652): qmi_client [3652] 13: pipe() system call, fd[0]=10, fd[1]=11
E/Diag_Lib( 3652): qmi_client [3652] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3652): qmi_client [3652] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3652): Sending signal ...... to read cmd data 
E/Diag_Lib( 3652): qmi error code.........:0
E/Diag_Lib( 3652): qmi sys error code.........:0
,E/Diag_Lib( 3652): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3652): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3652): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3652): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3652): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3652): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3652): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3652): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3652): qmi_init:  Created client handle b70ffb10
,E/Diag_Lib( 3652): qmi_client [3652] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3652): qmi_client [3652] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3652): Sending signal ...... to read cmd data 
E/Diag_Lib( 3652): qmi error code.........:0
,E/Diag_Lib( 3652): qmi sys error code.........:0
E/Diag_Lib( 3652): Setting the api flag to : 1
,E/Diag_Lib( 3652): qmi_client [3652] 13: sending 54 bytes on fd = 8
,E/WifiHW  ( 1015): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1015): ctrl_interface != /data/misc/wifi/sockets
,I/wpa_supplicant( 3655): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3655): rfkill: Cannot open RFKILL control device
D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,I/rmt_storage(  416): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb74531d0
I/rmt_storage(  416): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  416): wakelock acquired: 1, error no: 42
,I/rmt_storage(  416): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1220202776)
E/Diag_Lib( 3652): qmi_client [3652] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3652):  API Flag .............. 1 
,E/Diag_Lib( 3652):  Message ID ............... 92 
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/WifiStateMachine( 1015): setWifiState: enabling
,D/WifiStateMachine( 1015): Supplicant start successful
E/Diag_Lib( 3652): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3652): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3652): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3652): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3652): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3652): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3652): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3652): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3652): qmi_client [3652] 13: sending 880 bytes on fd = 8
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
E/Diag_Lib( 3652): qmi_client [3652] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3652): Sending signal ...... to read cmd data 
E/Diag_Lib( 3652): qmi error code.........:0
E/Diag_Lib( 3652): qmi sys error code.........:0
E/Diag_Lib( 3652): qmi_release: Released client handle ff
E/Diag_Lib( 3652): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_,Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3652): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3652): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3652): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3652): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3652): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3652): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3652): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3652): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3652): qmi_client [3652] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3652): qmi_client [3652] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3652): Sending signal ...... to read cmd data 
E/Diag_Lib( 3652): qmi error code.........:0
E/Diag_Lib( 3652): qmi sys error code.........:0
E/Diag_Lib( 3652): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3652] 13
E/Diag_Lib( 3652): qmi_client [3652] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3652): qmi_client [3652] 13: failed to locate client data
E/Diag_Lib( 3652): qmi_client [3652] 13: calling release of fd=8
E/Diag_Lib( 3652): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,D/WifiMonitor( 1015): startMonitoring(wlan0) with mConnected = false,
,W/XTWiFiOS( 1268): Active network info is not available
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/rmt_storage(  416): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  416): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  416): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1220202776) wakelock released: 1, error no: 0
I/rmt_storage(  416): 
E/Diag_Lib( 3655): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3655): Setting internal use port to rmnet0
,I/rmt_storage(  416): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb74531d0
,E/wpa_supplicant( 3655): baseband property is set to [msm]
,E/wpa_supplicant( 3655):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3655): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3655): card_info[i].card_state: 0x2
E/wpa_supplicant( 3655): card_info[i].error_code: 0x3
E/wpa_supplicant( 3655): SIM/USIM not ready
,E/wpa_supplicant( 3655): Error while reading SIM card status
,E/wpa_supplicant( 3655): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3655): card_info[i].card_state: 0x2
E/wpa_supplicant( 3655): card_info[i].error_code: 0x3
E/wpa_supplicant( 3655): SIM/USIM not ready
,I/wpa_supplicant( 3655): eap_proxy: Card not ready
,I/qcom-bluetooth( 3658): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3659): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3573): bluetooth satus is on
I/GKI_LINUX( 3573): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3573): btu_task pending for preload complete event
,D/bt_userial_mct( 3573): userial_open(port:0)
I/bt_userial_vendor( 3573): Done intiailizing UART
,I/bt_userial_vendor( 3573): Done intiailizing UART
I/bt_userial_mct( 3573): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3573): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 3573): Entering userial_read_thread()
,I/bt-btu  ( 3573): btu_task received preload complete event
I/        ( 3573): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3573): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3573): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3573): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3573): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3573): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3573): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3573): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3573): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3573): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3573): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3573): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3573): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3573): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3573): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3573): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f134049 
,E/bt-btm  ( 3573): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f134049 
,E/bt-btif ( 3573): Calling BTA_HhEnable
E/bt-btif ( 3573): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3573): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1015): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1015): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3573): Name is: XT1039
,I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3573): Scan Mode:21
I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3573): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:8 len:6
,D/BluetoothAdapterProperties( 3573): Adding bonded device:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 3573): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,I/bte_conf( 3573): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3573): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3573): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3573): hci lib postload completed
,I/bte_conf( 3573): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothPanServiceJni( 3573): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/BluetoothAdapterState( 3573): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3573): ScanMode =  21
D/BluetoothAdapterProperties( 3573): State =  11
D/BluetoothAdapterProperties( 3573): Setting state to 12
I/BluetoothAdapterState( 3573): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3573): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1015): Message: 60
,D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothHeadset( 1243): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3573): Entering On State
,D/BluetoothHeadset( 1243): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1243): onBluetoothStateChange: up=true
D/BluetoothPan( 1015): onBluetoothStateChange on: true
,D/BluetoothHeadset( 1015): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1107990088)( 3573): Get Bonded Devices being called
I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothA2dp( 1015): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 3573): Discoverable Timeout:120
,D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService( 1015): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3573): onReceive
,D/BluetoothMapService( 3573): STATE_ON
D/BluetoothManagerService( 1015): Message: 40
,D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothAdapterProperties( 3573): getBondedDevices: length=1
,D/BluetoothMapService( 3573): Map Service startRfcommSocketListener
,D/BluetoothMapService( 3573): Map Service initSocket
D/BluetoothAdapterService(1107990088)( 3573): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3573): getBondedDevices: length=1
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3573): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3573): SOCK FLAG = 1 ***********************
,I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3573): Scan Mode:21
,D/BluetoothAdapterService(1107990088)( 3573): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3573): getBondedDevices: length=1
,D/BluetoothMapService( 3573): Accepting socket connection...
,D/BluetoothAdapterService(1107990088)( 3573): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3573): getBondedDevices: length=1
,I/wpa_supplicant( 3655): Long line in configuration file truncated
,I/wpa_supplicant( 3655): rfkill: Cannot open RFKILL control device
,I/qcom-bt-wlan-coex( 3672): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,D/BluetoothPbapService( 3573): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3573): Handler(): got msg=1
,D/BluetoothManagerService( 1015): Message: 20
,D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43df3538:true
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3573): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3573): SOCK FLAG = 1 ***********************
D/BluetoothAdapterService(1107990088)( 3573): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3573): getBondedDevices: length=1
,E/wpa_supplicant( 3655): COUNTRY Code Recived
,E/wpa_supplicant( 3655): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3655): baseband property is set to [msm]
,E/wpa_supplicant( 3655):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3655): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3655): card_info[i].card_state: 0x2
E/wpa_supplicant( 3655): card_info[i].error_code: 0x3
E/wpa_supplicant( 3655): SIM/USIM not ready
,E/wpa_supplicant( 3655): Error while reading SIM card status
E/wpa_supplicant( 3655): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3655): card_info[i].card_state: 0x2
E/wpa_supplicant( 3655): card_info[i].error_code: 0x3
E/wpa_supplicant( 3655): SIM/USIM not ready
,I/wpa_supplicant( 3655): eap_proxy: Card not ready
D/WifiStateMachine( 1015): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: InitialState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1015): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131144
,D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): deferMessage: msg=131144
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131085
D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): deferMessage: msg=131085
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131149
D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1015): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147457
,D/WifiStateMachine( 1015): processMsg: SupplicantStartingState
D/WifiStateMachine( 1015): Supplicant connection established
,D/WifiStateMachine( 1015): setWifiState: enabled
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1268): Active network info is not available
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiConfigStore( 1015): Loading config and enabling all networks
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,E/WifiConfigStore( 1015): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3655): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1015): transitionTo: destState=DriverStartedState
,D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1015): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1015): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1015): setDetailed state, old =IDLE and new state=DISCONNECTED
,E/wpa_supplicant( 3655): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3655): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1015): Attempting to reconnect to wifi network ..
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/WifiStateMachine( 1015): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1015): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1015): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1015): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1015): invokeEnterMethods: DisconnectedState
D/dalvikvm( 1015): GC_EXPLICIT freed 22246K, 65% free 17883K/50212K, paused 4ms+11ms, total 183ms
,D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring up p2p0
,D/LocalBluetoothProfileManager( 3602): Adding local A2DP profile
,D/WifiMonitor( 1015): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1015): P2pEnablingState
D/WifiP2pService( 1015): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2p socket connection successful
D/WifiP2pService( 1015): P2pEnabledState
,D/WifiP2pService( 1015): sending p2p connection changed broadcast
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131144
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131085
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131152
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): set country code PL
D/BluetoothManagerService( 1015): Message: 30
,E/wpa_supplicant( 3655): COUNTRY Code Recived
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
E/wpa_supplicant( 3655): COUNTRY Code Recived
D/WifiStateMachine( 1015): handleMessage: X
D/LocalBluetoothProfileManager( 3602): Adding local HEADSET profile
D/BluetoothManagerService( 1015): Message: 30
D/WifiStateMachine( 1015): handleMessage: E msg.what=131162
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): set frequency band 2
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/WifiP2pService( 1015): DeviceAddress: f4:f1:e1:5c:43:c8
D/BluetoothManagerService( 1015): Message: 30
W/wpa_supplicant( 3655): wlan0: Failed to initiate AP scan
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131167
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=143371
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/BluetoothManagerService( 1015): Message: 30
D/WifiP2pService( 1015): MCC mode enabled 0
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
,D/LocalBluetoothProfileManager( 3602): Adding local MAP profile
,D/WifiP2pService( 1015): mP2pAutoConnectSupport = 0
D/BluetoothMap( 3602): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1015): Message: 30
D/WifiP2pService( 1015): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1015): InactiveState
D/WifiP2pService( 1015): InactiveState{ when=-22ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/WifiP2pService( 1015): P2pEnabledState{ when=-22ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): InactiveState{ when=-23ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-24ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3655): COUNTRY Code Recived
,E/wpa_supplicant( 3655): COUNTRY Code Recived
D/WifiP2pService( 1015): InactiveState{ when=-17ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-17ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothManagerService( 1015): Message: 30
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3602): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3602): finishStartingService: stopping service
,D/BluetoothAdapterService(1107990088)( 3573): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3573): getBondedDevices: length=1
,D/BluetoothA2dp( 3602): Proxy object connected
,D/A2dpProfile( 3602): Bluetooth service connected
,D/BluetoothHeadset( 3602): Proxy object connected
,D/HeadsetProfile( 3602): Bluetooth service connected
,D/BluetoothInputDevice( 3602): Proxy object connected
,D/HidProfile( 3602): Bluetooth service connected
,D/BluetoothPan( 3602): BluetoothPAN Proxy object connected
D/PanProfile( 3602): Bluetooth service connected
D/BluetoothMap( 3602): Proxy object connected
,D/MapProfile( 3602): Bluetooth service connected
,D/BluetoothMap( 3602): getConnectedDevices()
,D/BluetoothPbap( 3602): Proxy object connected
,D/PbapServerProfile( 3602): Bluetooth service connected
,V/BluetoothFtpReceiver( 3573): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3573): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1333): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1333): Proximity feature is not enabled.
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothFtpService( 3573): Ftp Service onCreate
I/BluetoothFtpService( 3573): FFFFFtp Service onCreate
V/BluetoothFtpService( 3573): Starting FTP service
,W/BluetoothAdapter( 3573): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3573): SOCK FLAG = 0 ***********************
,V/BluetoothFtpService( 3573): Ftp Service onStartCommand
V/BluetoothFtpService( 3573): action: android.bluetooth.adapter.action.STATE_CHANGED
,I/BtOppRfcommListener( 3573): Accept thread started.
,V/BluetoothFtpService( 3573): Handler(): got msg=1
V/BluetoothFtpService( 3573): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3573): Ftp Service initSocket
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3573): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3573): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3573): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3573): Run Accept thread
,D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  274): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  274): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): wifi_connect_to_supplicant, current pid is = 274
D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  274): wifi_close_sockets: Exit
E/MDMCTBK (  274): Attach monitor thread
,I/MDMCTBK (  274): createWifiMonitorThread: Started the wifi monitor thread -1221084336
,D/MDMCTBK (  274): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/wpa_supplicant( 3655): wlan0: Failed to initiate AP scan
D/MDMCTBK (  274): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  274): Event received = Failed to initiate AP scan
,D/WifiP2pService( 1015): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledStateupdate channel list
,D/MDMCTBK (  274): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  274): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0:
D/MDMCTBK (  274): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 06:
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 06:
D/MDMCTBK (  274): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  274): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 38:
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 38:
D/MDMCTBK (  274): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 06:
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 06:
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 3655): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
I/wpa_supplicant( 3654): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3654): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
E/wpa_supplicant( 3655): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1015): handleMessage: E msg.what=147461
D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
,D/WifiStateMachine( 1015): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
,D/TCMD    (  480): NL - Read 312 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 88 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
I/wpa_supplicant( 3655): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 3655): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3655): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 80 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
,D/WifiStateMachine( 1015): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3655): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3655): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  274): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
,I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
,I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1220933040
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1015): processMsg: DisconnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): Network connection established
,D/WifiStateMachine( 1015): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1015): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1015): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1015): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1015): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-57ms what=147462 obj=android.net.wifi.StateChangeResult@4210e990 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-32ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4274d298 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=196612
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1015): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4296d160 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4296d160 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 8
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 8e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 8e
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  480): NL - Read 56 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/WifiStateMachine( 1015): handleMessage: E msg.what=147461
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiP2pService( 1015): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@429731f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@429731f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@429731f0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): handleMessage: X
,I/jxcore-log( 3527): Attempting to connect to the test coordinator server
I/jxcore-log( 3527): 
,D/TCMD    (  480): NL - Read 60 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 20
,D/TCMD    (  480): Listening for incoming client connection request
,D/WifiStateMachine( 1015): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131215
D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=0 what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
,D/WifiStateMachine( 1015): processMsg: DriverStartedState
,D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1015): processMsg: ObtainingIpState
D/WifiStateMachine( 1015): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1015): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): DHCP successful
D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1015): Calling ARP set with IP = 192.168.1.123
D/WifiStateMachine( 1015): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1015): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState enter
D/WifiStateMachine( 1015): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=151572
D/WifiStateMachine( 1015): processMsg: VerifyingLinkState
D/WifiStateMachine( 1015): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=135190
D/WifiStateMachine( 1015): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1015): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1015): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1015): CaptivePortalCheckState enter
,D/WifiStateMachine( 1015): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1015): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine( 1015): handleMessage: X
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131092
D/WifiStateMachine( 1015): processMsg: CaptivePortalCheckState
,D/WifiStateMachine( 1015): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1015): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1015): WiFi NOT Tethered!
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
E/ConnectivityService( 1015): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f738
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1015): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
,D/WifiStateMachine( 1015): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131092
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
,D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1288): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1288): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1288): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1015): WiFi NOT Tethered!
,E/ConnectivityService( 1015): Unexpected mtu value: android.net.wifi.WifiStateTracker@4220f738
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1015): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1288): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1288): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1288): onReceive() - done, currentInetCondition=0
,D/PollingManager( 1533): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1015): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        ( 1015): Setting time of day to sec=1447842313
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,W/        ( 1015): Unable to set rtc to 1447842313: Invalid argument
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,D/PollingManager( 1533): now: 286780 ,futureTime: 82549206
,D/PollingManager( 1533): Polling alarm set to expire at: 82549206 Current Time: 286781
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1015): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,E/ActivityThread( 1533): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1533): registerApp(): CCE
I/CCE     ( 1533): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1533): Registering with Alarm Manager to restart CCE
,D/MMApiWebService( 1533): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
,D/CCE     ( 1533): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1533): isRequestAllowed(): already have outstanding request ... ignoring request
,D/MMApiWebService( 1533): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1533): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/OtaApp  ( 1533): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1533): [debug] > CusSM.onRadioUp
,D/MMApiWebService( 1533): generating token using payload instead of using session token
,D/PollingManager( 1533): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/PollingManager( 1533): now: 286865 ,futureTime: 82549206
,D/PollingManager( 1533): Polling alarm set to expire at: 82549206 Current Time: 286866
,I/openssl ( 3032): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3032): Crypto mode 0 already enabled
D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1533): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/ActivityManager( 1015): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3780 uid=10056 gids={50056, 3003, 1028, 1015}
,E/ActivityThread( 1533): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1533): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1533): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1533): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1533): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1533): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1533): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1533): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3801 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,V/MmsConfig( 3801): mnc/mcc: 
V/MmsConfig( 3801): tag: bool value: enabledMMS - true
,V/MmsConfig( 3801): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3801): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3801): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3801): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3801): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3801): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3801): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3801): tag: int value: recipientLimit - 20
V/MmsConfig( 3801): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 3801): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3801): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3801): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3801): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 3801): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3801): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3801): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3801): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/VacuumService( 1333): Vacuum at: now=1447842314069 tag=VacuumService
I/dalvikvm( 1360): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1360): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1360): VFY: replacing opcode 0x6e at 0x0033
,I/ActivityManager( 1015): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3825 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1015): Killing 3379:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DelayedSyncController( 3780): Delaying sync.
,I/dalvikvm( 1208): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 1208): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1208): VFY: replacing opcode 0x6e at 0x0033
,D/TelephonyProvider( 1243): Column apn id key is 'apn_id'
,D/GpsLocationProvider( 1015): NTP server returned: 1447842310810 (Wed Nov 18 11:25:10 CET 2015) reference: 283869 certainty: 16 system time offset: -3314
,E/LocSvc_ApiV02( 1015): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/dalvikvm( 1243): GC_EXPLICIT freed 1388K, 45% free 9518K/17224K, paused 2ms+11ms, total 79ms
,E/Auth.Api.Credentials( 1360): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1015): Killing 3102:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/MobileConnectivityChangeReceiver( 3825): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3825): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3825): onOtaspChanged old =0, new =3
V/PhoneMonitor( 3825): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3845 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3405:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1360): Checkin interval check for package: unspecified last checkin: 1447838179351 min interval config: 0 actual interval: 4134866
,D/dalvikvm( 1208): GC_EXPLICIT freed 1503K, 41% free 10303K/17224K, paused 5ms+5ms, total 94ms
I/CheckinService( 1360): Checking schedule, now: 1447842314240 next: 1447838209317
,I/CheckinService( 1360): active receiver: enabled
,E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423c0888)
,I/CheckinService( 1360): Preparing to send checkin request
,I/EventLogService( 1360): Accumulating logs since 1447841820175
,V/WebViewChromiumFactoryProvider( 3845): Binding Chromium to main looper Looper (main, tid 1) {4209d778}
,I/LibraryLoader( 3845): Expected native library version number "",actual native library version number ""
,I/chromium( 3845): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3845): Initializing chromium process, renderers=0
,D/dalvikvm( 1015): GC_EXPLICIT freed 1757K, 65% free 17888K/50212K, paused 4ms+10ms, total 100ms
,E/AudioManagerAndroid( 3845): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3845): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3845): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3845): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3845): Local Branch: 
I/Adreno-EGL( 3845): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3845): Local Patches: NONE
I/Adreno-EGL( 3845): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/DelayedSyncController( 3780): Delaying sync.
,D/dalvikvm( 1533): GC_CONCURRENT freed 2991K, 38% free 10766K/17224K, paused 3ms+3ms, total 36ms
,I/CheckinRequestBuilder( 1360): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1015): New client listening to asynchronous messages
,E/ActivityThread( 1360): Failed to find provider info for com.google.android.wearable.settings
,W/chromium( 3845): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3845): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3845): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1333): GC_EXPLICIT freed 1175K, 39% free 10554K/17224K, paused 2ms+4ms, total 37ms
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1015): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3889 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 3889): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3889): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 3889): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3889): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3889): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 3889): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3889): install
,I/MultiDex( 3889): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/NSApplication( 3845): Starting up...
,I/MultiDex( 3889): loading existing secondary dex files
,I/MultiDex( 3889): load found 3 secondary dex files
,I/MultiDex( 3889): install done
,I/ImageResourceManager( 3433): ImageResourceManager: uninitalized
,I/iu.Environment( 3433): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3433): SYNC; picasa accounts
,D/dalvikvm( 3889): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3889): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3889): VFY: replacing opcode 0x62 at 0x000a
,I/ActivityManager( 1015): Killing 3078:android.process.acore/u0a10 (adj 15): empty #9
,D/dalvikvm( 3889): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/dalvikvm( 3889): VFY: unable to resolve instance field 46
D/dalvikvm( 3889): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 3889): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 3889): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3889): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 3889): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3889): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 3889): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x420a3db0
,D/dalvikvm( 3889): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x420a3db0
,D/dalvikvm( 3889): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x420a3db0, skipping init
,D/dalvikvm( 3889): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x420a3db0
,D/dalvikvm( 3889): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x420a3db0
V/JNIHelp ( 3889): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/iu.UploadsManager( 3433): num queued entries: 0
,I/iu.UploadsManager( 3433): num updated entries: 0
,I/iu.SyncManager( 3433): NEXT; no task
,D/MMApiWSBase( 1533): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1533): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1533): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/iu.SyncManager( 1360): SYNC; picasa accounts
,D/NetworkLogImpl( 1360): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1360): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1360): num queued entries: 0
,I/iu.UploadsManager( 1360): num updated entries: 0
,I/iu.SyncManager( 1360): NEXT; no task
,D/Checkin ( 1533): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1533): handleGetNotificationsResponse(): got 0; more=false
,D/dalvikvm( 3889): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x420a3db0
,D/dalvikvm( 3889): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x420a3db0
D/dalvikvm( 3889): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x420a3db0
,D/dalvikvm( 3889): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x420a3db0
,D/DEBUG   ( 1533): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1533): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1533): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=1
,D/WifiStateMachine( 1015): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
I/openssl ( 3032): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3032): Crypto mode 0 already enabled
D/WifiStateMachine( 1015): handleMessage: E msg.what=131215
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1015): handleMessage: X
D/ConnectivityService( 1015): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1015):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService( 1015): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=true
,D/MobileConnectivityChangeReceiver( 3825): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3825): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3433): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3918 uid=10007 gids={50007, 3003}
,I/ProviderInstaller( 3889): Installed default security provider GmsCore_OpenSSL
,D/MMApiProvisionService( 1533): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"168602","deviceId":"1135300315450105856"}
D/MMApiProvisionService( 1533): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1533): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1533): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1533): handleResponse(): Session Expiration alarm set to expire at: Fri Nov 20 10:15:17 CET 2015
,D/MMApiProvisionService( 1533): _setMMApiCredInfo: storing credential info 
,E/MMApiProvisionService( 1533): handleResponse(): no settings sent by the server:
,D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
,D/ExtensionsFactory( 3918): No custom extensions.
,D/MMApiWebService( 1533): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,I/dalvikvm( 3889): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 3889): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3889): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3889): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 3889): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3889): VFY: replacing opcode 0x6e at 0x0220
I/ActivityManager( 1015): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3936 uid=10015 gids={50015, 1028}
I/ActivityManager( 1015): Killing 3139:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/GCM     ( 1333): GCM config loaded
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3951 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3602:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1015): Client connection lost with reason: 4
,V/AlarmClock( 3936): AlarmInitReceiver android.intent.action.TIME_SET
I/dalvikvm( 3889): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3889): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 3889): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 3889): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 3889): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3889): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 3889): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3889): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 3889): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 3889): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 3889): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,I/AlarmClock( 3936): Displaying next alarm time: ''
,V/AlarmClock( 3936): AlarmInitReceiver finished
,I/ActivityManager( 1015): Killing 3032:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CalendarProvider2( 3951): Created com.android.providers.calendar.CalendarAlarmManager@420baff0(com.android.providers.calendar.CalendarProvider2@420b2ba8)
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/QSEECOMAPI: (  278): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/QSEECOMAPI: (  278): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  278): App is not loaded in QSEE
,D/QSEECOMAPI: (  278): Loaded image: APP id = 3
D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5141000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5141000
,D/UdcCache:FPQuery( 1360): Bootstrapping UDC settings cache for all accounts
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
I/ActivityManager( 1015): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3971 uid=10098 gids={50098}
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1473345566
D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 3971): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x420a7188, skipping init
D/TimeService( 3971): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1447842315464
D/        ( 3971): TimeServiceNative: User Time to be set is 1447842315464
D/QC-time-services( 3971): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3971): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3971): Lib:time_genoff_operation: pargs->ts_val = 1447842315464
,D/QC-time-services(  400): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3971): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  400): Daemon:Received base = 2, unit = 1, operation = 0,value = 1447842315464
D/QC-time-services(  400): Daemon:genoff_opr: Base = 2, val = 1447842315464, operation = 0
D/QC-time-services(  400): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/18/115 10:19:26
D/QC-time-services(  400): Daemon:Value read from RTC seconds = 1447841966000
D/QC-time-services(  400): Daemon:new time 1447842315464 
D/QC-time-services(  400): Daemon: delta 349464 genoff 349464 
D/QC-time-services(  400): Daemon:genoff_persistent_update: Writing genoff = 349464 to memory
D/QC-time-services(  400): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  400): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  400): Updating the TOD offset
D/QC-time-services(  400): Daemon:genoff_persistent_update: Writing genoff = 349464 to memory
D/QC-time-services(  400): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  400): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  400): Daemon:Update to modem bit set
D/QC-time-services(  400): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  400): Daemon: Base = 2, Value being sent to MODEM = 18446743757745101080
,E/QC-time-services( 3971): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  400): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  400): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1360): Checkin interval check for package: unspecified last checkin: 1447838179351 min interval config: 0 actual interval: 4136184
,D/DEBUG   ( 1533): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1533): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1533): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1533): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1533): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1015): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1533
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/dalvikvm( 3889): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4228bbc8
D/dalvikvm( 3889): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4228bbc8
,D/dalvikvm( 3889): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4228bbc8, skipping init
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1533): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1015): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1533
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1015): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,133
D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/ConnectivityService( 1015): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1288): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
D/DEBUG   ( 1533): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/ModemStatsDSDetect( 1288): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1288): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1288): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/SundryService( 1533): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
,I/ActivityManager( 1015): Activity reported stop, but no longer stopping: ActivityRecord{4243b198 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
D/WaitableIntentService( 1533): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1533): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1533): unbindWebServices(): un-registering our AIDL callback...
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/dalvikvm( 1360): GC_CONCURRENT freed 1339K, 33% free 11696K/17224K, paused 5ms+6ms, total 47ms
,D/WearableService( 1208): callingUid 10022, callindPid: 1208
,E/MDM     ( 1208): [75] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1333): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1333): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1333): Proximity feature is not enabled.
,D/LocationInitializer( 1360): Restart initialization of location
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 3889): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,V/GmsCoreStatsServiceLauncher( 1360): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/NativeLibraryUtils( 3889): Install completed successfully. count=13 extracted=0
,D/DEBUG   ( 1533): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,W/ContextImpl( 1533): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1533): bindWebServices(): registering our AIDL callback...
I/SundryService( 1533): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
D/GetNotificationsWS( 1533): onServiceConnected()
I/SundryService( 1533): Received shoulder tap
,D/GetNotificationsWS( 1533): onServiceConnected(): Registered for remote service callbacks...
,D/dalvikvm( 3993): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 3889): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3889): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 82ms
,D/WaitableIntentService( 1533): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,I/Adreno-EGL( 3889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3889): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3889): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3889): Local Branch: 
I/Adreno-EGL( 3889): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3889): Local Patches: NONE
I/Adreno-EGL( 3889): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/GetNotificationsWS( 1533): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1533): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1533): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1533): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
,W/GCoreFlp( 1208): No location to return for getLastLocation()
,W/FusedLocationProvider( 1333): location=null
,D/GetConfigurationSnapshotOperation( 1333): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/Adreno-EGL( 3889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3889): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3889): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3889): Local Branch: 
I/Adreno-EGL( 3889): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3889): Local Patches: NONE
I/Adreno-EGL( 3889): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/PhenotypeFlagCommitter( 1333): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1333): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1333): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/CalendarProvider2( 3951): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3951): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/AlertReceiver( 3918): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/AlertService( 3918): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3760836069
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 1333): GC_CONCURRENT freed 1611K, 37% free 10902K/17224K, paused 3ms+5ms, total 31ms
,D/MMApiWSBase( 1533): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1533): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1533): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/Checkin ( 1533): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1533): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1533): Received intent : com.motorola.ccc.notification.action.NOTIFY
,D/dalvikvm( 1015): GC_EXPLICIT freed 807K, 65% free 17849K/50212K, paused 4ms+10ms, total 91ms
I/SundryService( 1533): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1533): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1533): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1533): unbindWebServices(): un-registering our AIDL callback...
,D/GetCommittedConfigurationOperation( 1333): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1333):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1333): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1333): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Settings( 3889): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 3889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3889): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3889): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3889): Local Branch: 
I/Adreno-EGL( 3889): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3889): Local Patches: NONE
I/Adreno-EGL( 3889): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3889): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3889): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3889): Local Branch: 
I/Adreno-EGL( 3889): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3889): Local Patches: NONE
I/Adreno-EGL( 3889): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1360): Classify the device as Phone.
,I/CheckinTask( 1360): Sending checkin request (11772 bytes)
,D/GetCommittedConfigurationOperation( 1333): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1333): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/CheckinRequestBuilder( 1360): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1360): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1360): Classify the device as Phone.
,I/CheckinTask( 1360): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1360): Checking schedule, now: 1447842317786 next: 1448435387779
,I/CheckinService( 1360): active receiver: disabled
,D/CheckinService( 1360): Recording last checkin time for package unspecified as 1447842317799
,D/GCM     ( 1333): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 3845): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 3918): no sender configured
,D/AlertService( 3918): Beginning updateAlertNotification
,D/AlertService( 3918): No fired or scheduled alerts
,D/AlertService( 3918): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3918): No events found starting within 1 week.
I/ActivityManager( 1015): Killing 3801:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Killing 3825:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1015): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1015): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1015): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1015): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1015): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1015): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1015): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1015): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4038 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/Launcher( 1302): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
I/Launcher( 1302): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1208): DISABLE
,I/Babel   ( 4038): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4038): MmsConfig.loadMmsSettings
I/GCoreNlp( 1208): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/Babel   ( 4038): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4038): MmsConfig.loadFromDatabase
,E/Babel   ( 4038): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4038): MmsConfig.loadFromResources
,E/Babel   ( 4038): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4038): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1015): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4070 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1015): Killing 3780:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4088 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3845:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2167): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4106 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1015): Killing 3951:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3433): GC_CONCURRENT freed 625K, 5% free 16453K/17224K, paused 2ms+2ms, total 42ms
,D/dalvikvm( 3433): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm-heap( 3433): Grow heap (frag case) to 19.836MB for 1821008-byte allocation
,D/dalvikvm( 1333): GC_CONCURRENT freed 1977K, 37% free 10855K/17224K, paused 2ms+4ms, total 47ms
,I/dalvikvm( 4106): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4106): VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x000d
,I/ContactLocale( 4070): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 4106): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4106): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4106): VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4106): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4106): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x000a
,I/InternalIcingCorporaPro( 2167): UpdateCorporaTask done [took 252 ms] updated apps [took 252 ms] 
,D/Finsky  ( 4106): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4106): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4106): VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4106): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4106): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4106): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4106): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4106): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4106): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x0392
I/dalvikvm( 4106): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4106): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x0398
,I/ActivityManager( 1015): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4141 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/dalvikvm( 4106): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4106): VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4106): Skipping gmscore version check
,D/Finsky  ( 4106): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4106): [1] 2.run: Finished loading 1 libraries.
,I/dalvikvm( 4106): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4106): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1015): Killing 3936:com.android.deskclock/u0a15 (adj 15): empty #9
I/ActivityManager( 1015): Killing 3971:com.qualcomm.timeservice/u0a98 (adj 15): empty #10
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1360): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1360): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1360): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4141): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x420a3288, skipping init
I/openssl ( 4141): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4141): Crypto mode 0 already enabled
,D/Finsky  ( 4106): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4106): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/jxcore-log( 3527): Attempting to connect to the test coordinator server
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Attempting to connect to the test coordinator server
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Attempting to connect to the test coordinator server
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Attempting to connect to the test coordinator server
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Attempting to connect to the test coordinator server
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Attempting to connect to the test coordinator server
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Test app app.js loaded
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":0}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): LogCallback not set !!!!
I/jxcore-log( 3527): 
,I/Choreographer( 3527): Skipped 1267 frames!  The application may be doing too much work on its main thread.
,W/IInputConnectionWrapper( 3527): showStatusIcon on inactive InputConnection
,I/chromium( 3527): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector connect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector connect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector connect called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector connect called
I/jxcore-log( 3527): 
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3527): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): got start_tests event with data : {"data":{"devices":{"ios":3,"android":17}}}
I/jxcore-log( 3527): 
,V/AlarmManager( 1015): sending alarm Alarm{42102f30 type 2 android}
,I/jxcore-log( 3527): {"type":"end","test":0}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"test connectionTable table building and cleanup","id":1}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DB value for ThaliReplicationManager is: "bogus",
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1447842346713},"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":1}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: undefined : test connectionTable table building and cleanup", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : Cleanup was called, this table is no longer live.", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":2}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":3}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":3}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":4}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: undefined : test connectionTable emitting events for peerIds", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":5}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":6}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1015): sending alarm Alarm{420b3880 type 3 android}
,I/jxcore-log( 3527): {"type":"end","test":6}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"start with bad friendly names","id":7}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":7}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: undefined : start with bad friendly names", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":8}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":9}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":9}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 10 isOK: undefined : make sure startIdentityExchange sets things up properly", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: Vp3iu4jUNgQ+EGtyEaM2Og==;Matt
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":53838,"expected":53838,"test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"Vp3iu4jUNgQ+EGtyEaM2Og==;Matt","expected":"Vp3iu4jUNgQ+EGtyEaM2Og==;Matt","test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":10}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 11 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":11}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":12}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 12 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":12}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":13}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: MWeDla7wvVjCSAKIBrAK0w==;Toby
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":42846,"expected":42846,"test":13,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"MWeDla7wvVjCSAKIBrAK0w==;Toby","expected":"MWeDla7wvVjCSAKIBrAK0w==;Toby","test":13,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 13 isOK: undefined : make sure we get an error if we call start and then immediately call stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 14 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":14}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":15}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 15 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":15}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Make sure stop is clean from start","id":16}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: CPJGoQmPuv0i0TAVGngQjg==;Luke
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":56169,"expected":56169,"test":16,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"CPJGoQmPuv0i0TAVGngQjg==;Luke","expected":"CPJGoQmPuv0i0TAVGngQjg==;Luke","test":16,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":16}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 16 isOK: undefined : Make sure stop is clean from start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : Should not have gotten error on startIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : Should not have gotten error on stopIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : State should be Stopped", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 17 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":17}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":18}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 18 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3527): {"type":"end","test":18}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: oO1tfqqh1M/Dbb0lj+AMwg==;Jukka
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":37243,"expected":37243,"test":19,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"oO1tfqqh1M/Dbb0lj+AMwg==;Jukka","expected":"oO1tfqqh1M/Dbb0lj+AMwg==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":19}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 19 isOK: undefined : Make sure stop is clean from stop execute identity exchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 20 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":20}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":21}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 21 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3527): {"type":"end","test":21}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: Koy6boZEnR37rkGTcounJw==;Doug
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":59962,"expected":59962,"test":22,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"Koy6boZEnR37rkGTcounJw==;Doug","expected":"Koy6boZEnR37rkGTcounJw==;Doug","test":22,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":22}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 22 isOK: undefined : make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 23 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":23}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":24}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 24 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":24}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: eZLq9BDck1ThfZlapyHLrA==;David
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":38422,"expected":38422,"test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"eZLq9BDck1ThfZlapyHLrA==;David","expected":"eZLq9BDck1ThfZlapyHLrA==;David","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: eZLq9BDck1ThfZlapyHLrA==;David
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":38422,"expected":38422,"test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"eZLq9BDck1ThfZlapyHLrA==;David","expected":"eZLq9BDck1ThfZlapyHLrA==;David","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":25}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 25 isOK: undefined : illegal method combinations", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 26 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":26}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":27}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 27 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":27}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 28 isOK: undefined : do an identity exchange and get code multiple times to make sure we do not hork state", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":623232,"expected":623232,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":978496,"expected":978496,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":657920,"expected":657920,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":119872,"expected":119872,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":581696,"expected":581696,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 75 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 76 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 77 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 78 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 79 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 80 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 81 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 82 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":20096,"expected":20096,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 83 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 84 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 85 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 86 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 87 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 88 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 89 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 90 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 91 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":477888,"expected":477888,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 92 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 93 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 94 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 95 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 96 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 97 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 98 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 99 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 100 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 101 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 102 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 103 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 104 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 105 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 106 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 107 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 108 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 109 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 110 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 111 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 112 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":924736,"expected":924736,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 113 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 114 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 115 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 116 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 117 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 118 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 119 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":490048,"expected":490048,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 120 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 121 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 122 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 123 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 124 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 125 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 126 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 127 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 128 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 129 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 130 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 131 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 132 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 133 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 134 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":712128,"expected":712128,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: JkjPmQeOJ8534dx0vtHsIA==;John
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":58350,"expected":58350,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"JkjPmQeOJ8534dx0vtHsIA==;John","expected":"JkjPmQeOJ8534dx0vtHsIA==;John","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO identityExchange We will advertise the following device name as we start: XixyNcE2FGnDhOjX0o/2fQ==;Srikanth
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":47134,"expected":47134,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","expected":"XixyNcE2FGnDhOjX0o/2fQ==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/cb request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 135 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 136 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 137 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 138 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 139 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 140 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 141 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 142 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 143 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 144 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 145 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO smallerHash Making /identity/rnmine request to pkOther value XixyNcE2FGnDhOjX0o/2fQ==
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 146 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 147 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 148 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 149 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 150 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":792704,"expected":792704,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":28}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 151 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 152 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 153 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 154 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 155 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 156 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 157 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 158 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 159 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 160 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 161 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 162 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 163 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 164 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 29 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":29}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":30}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 30 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":30}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":31}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 31 isOK: undefined : test compareEqualSizeBuffers", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 32 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":32}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":33}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 33 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":33}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":34}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 34 isOK: undefined : Make sure we return 404 before hitting start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 35 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":35}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":36}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 36 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":36}
I/jxcore-log( 3527): 
,E/jxcore-log( 3527): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 3527): 
,E/jxcore-log( 3527): Trace: 
E/jxcore-log( 3527):     at Console.prototype.trace@console.js:165:13
E/jxcore-log( 3527):     at addListener@events.js:140:7
E/jxcore-log( 3527):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 3527):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 3527):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 3527):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 3527):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 3527):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,E/jxcore-log( 3527): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 3527): 
,E/jxcore-log( 3527): Trace: 
E/jxcore-log( 3527):     at Console.prototype.trace@console.js:165:13
E/jxcore-log( 3527):     at addListener@events.js:140:7
E/jxcore-log( 3527):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 3527):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 3527):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 3527):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 3527):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 3527):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":37}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 37 isOK: undefined : Random path after start, need 404", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 38 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":38}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":39}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 39 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":39}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":40}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":40,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":40,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"B0dpj+e/3rarWHKEmkz06A==","expected":"B0dpj+e/3rarWHKEmkz06A==","test":40,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":40,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":40}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":41}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 40 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 41 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":41}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":42}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 42 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":42}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":43}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":43,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":43,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"cpaPEWMOWTesxXI7bIPu0A==","expected":"cpaPEWMOWTesxXI7bIPu0A==","test":43,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":43,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":43}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":44}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 43 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 44 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1015): sending alarm Alarm{441c29a0 type 3 android}
,I/jxcore-log( 3527): {"type":"end","test":44}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":45}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 45 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/dalvikvm( 1015): Jit: resizing JitTable from 8192 to 16384
,I/jxcore-log( 3527): {"type":"end","test":45}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Confirm we get wrongPeer on cb if we give hash other than expected","id":46}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":46,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"yPd8BedE0uWlb2i0otyRCQ==","expected":"yPd8BedE0uWlb2i0otyRCQ==","test":46,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":46,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":46}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":47}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 46 isOK: undefined : Confirm we get wrongPeer on cb if we give hash other than expected", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 47 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":47}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":48}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 48 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":48}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)","id":49}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":49,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"ppsYNg2loeU/gtlCp8o3gA==","expected":"ppsYNg2loeU/gtlCp8o3gA==","test":49,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":49,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":49}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":50}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 49 isOK: undefined : Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 50 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":50}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":51}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 51 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":51}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"NoIdentityExchange after start & stop","id":52}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 52 isOK: undefined : NoIdentityExchange after start & stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"zPy7YC4CQaWXURdDR+/4Ng==","expected":"zPy7YC4CQaWXURdDR+/4Ng==","test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:39207/identity/cb","data":{"cbValue":"+l1I5u+w6y1E2kOceE1X5l8pF+j27ucWop5K4xkLVQg=","pkMine":"z5zbsB6FaemS1SpwBQpxcA=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-7fW3cQWPtzloNvvyDXUszw\"","date":"Wed, 18 Nov 2015 10:27:17 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"zPy7YC4CQaWXURdDR+/4Ng==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"zPy7YC4CQaWXURdDR+/4Ng==","expected":"zPy7YC4CQaWXURdDR+/4Ng==","test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:32834/identity/rnmine","data":{"rnMine":"hkkR0//LrnltVxDrwCXlBA==","pkOther":"JOk2HoFEvQsbbeYhOPh1wg=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-7fW3cQWPtzloNvvyDXUszw\"","date":"Wed, 18 Nov 2015 10:27:17 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"zPy7YC4CQaWXURdDR+/4Ng==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"zPy7YC4CQaWXURdDR+/4Ng==","expected":"zPy7YC4CQaWXURdDR+/4Ng==","test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:60337/identity/cb","data":{"cbValue":"/5A1rUS9lrOul1d3HE9EDS20SVOaimAvSUlywM74Iyg=","pkMine":"JslHc6vH9UskgiyuQ2dfVA=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-7fW3cQWPtzloNvvyDXUszw\"","date":"Wed, 18 Nov 2015 10:27:17 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"zPy7YC4CQaWXURdDR+/4Ng==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"zPy7YC4CQaWXURdDR+/4Ng==","expected":"zPy7YC4CQaWXURdDR+/4Ng==","test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":52}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":53}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 53 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":53}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":54}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 54 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":54}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"cbRequest - bad request bodies","id":55}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 55 isOK: undefined : cbRequest - bad request bodies", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":" ","pkMine":"0+S+BxJyIo0uBiE0yRI6/Q=="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"{@#{$@#{$","pkMine":"VV8J7s2Tk0IrX1XBjhqR3g=="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"0kyv/7uu/o/2d6/5q/vTNJcn37PtVlkg30/4EZLtbuEs","pkMine":"hXQdwAnGxGblL+Wzln+fWw=="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"z5c/TNO9XBLJ23BxFbhwAx80OnSUjMuHCHjVAziluw==","pkMine":"MvWXQN20KWvvTjI/fFtaeA=="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0Pe5nJ6IHgO+NShasPZ13CzBLOWW6mv4jcCP8CLPHwA=","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"gMorYiWwVgY6zigSqnOf/03zWFxm1ZpmUlGoQUffZ3U=","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"1C+Qwinst8Kww3IRNQSMec0KLljW/L1NTmXKBuRFdIU=","pkMine":"VOlWEbFNvX2dltWTz2poezk="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"WCrfYdfSaQ6ZbO+L1yuMyUpsx2pEve+z+n0HJW+g1Tc=","pkMine":"x9ZoPf7kxDqKUFJVlNNB"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"VOlWEbFNvX2dltWTz2poezk="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"x9ZoPf7kxDqKUFJVlNNB"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"VOlWEbFNvX2dltWTz2poezk="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"x9ZoPf7kxDqKUFJVlNNB"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0kyv/7uu/o/2d6/5q/vTNJcn37PtVlkg30/4EZLtbuEs","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0kyv/7uu/o/2d6/5q/vTNJcn37PtVlkg30/4EZLtbuEs","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0kyv/7uu/o/2d6/5q/vTNJcn37PtVlkg30/4EZLtbuEs","pkMine":"VOlWEbFNvX2dltWTz2poezk="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"0kyv/7uu/o/2d6/5q/vTNJcn37PtVlkg30/4EZLtbuEs","pkMine":"x9ZoPf7kxDqKUFJVlNNB"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"z5c/TNO9XBLJ23BxFbhwAx80OnSUjMuHCHjVAziluw==","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"z5c/TNO9XBLJ23BxFbhwAx80OnSUjMuHCHjVAziluw==","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"z5c/TNO9XBLJ23BxFbhwAx80OnSUjMuHCHjVAziluw==","pkMine":"VOlWEbFNvX2dltWTz2poezk="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"z5c/TNO9XBLJ23BxFbhwAx80OnSUjMuHCHjVAziluw==","pkMine":"x9ZoPf7kxDqKUFJVlNNB"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/cb request with a bum pkMine - {}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":17,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":18,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":20,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): {"id":22,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":24,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":25,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":26,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":28,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":32,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":33,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":35,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
I/jxcore-log( 3527): {"id":37,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":39,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":40,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":41,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":43,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":47,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":48,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":50,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":52,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":54,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":55,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":56,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":58,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":62,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":63,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":65,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":67,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":69,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":70,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":71,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":73,"ok":true,"name":"should be equal","operator":"equal","actual":"NEC6dyrQHflvf4hwlsbv1w==","expected":"NEC6dyrQHflvf4hwlsbv1w==","test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":55}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":56}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 56 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":56}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":57}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 57 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":57}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"re-do cb (to check we can reset) and make sure rnOther changes","id":58}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"iRhWPuXucdytWSQ+SJvheA==","expected":true,"test":58,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"lCywYOBenH0rA9R0r/Z8Bg==","expected":"lCywYOBenH0rA9R0r/Z8Bg==","test":58,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"iRhWPuXucdytWSQ+SJvheA==","test":58,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"lCywYOBenH0rA9R0r/Z8Bg==","expected":"lCywYOBenH0rA9R0r/Z8Bg==","test":58,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 58 isOK: undefined : re-do cb (to check we can reset) and make sure rnOther changes", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"lCywYOBenH0rA9R0r/Z8Bg==","expected":"lCywYOBenH0rA9R0r/Z8Bg==","test":58,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":58}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":59}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 59 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":59}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":60}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 60 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":60}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther","id":61}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"IW/L32lgq4Svg/DTtou+NA==","expected":true,"test":61,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"XrUeYe1skEY1mO08YaD+Uw==","test":61,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 61 isOK: undefined : good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[94,181,30,97,237,108,144,70,53,152,237,60,97,160,254,83],"expected":true,"test":61,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":822848,"expected":822848,"test":61,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":61}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":62}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 62 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":62}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":63}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 63 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":63}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"do a successful cb and successful rnmine and then repeat the rnmine","id":64}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"uhwdALyhOgIkXPjfUxZ3pQ==","expected":true,"test":64,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[186,28,29,0,188,161,58,2,36,92,248,223,83,22,119,165],"expected":true,"test":64,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":163008,"expected":163008,"test":64,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":64}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":65}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 64 isOK: undefined : do a successful cb and successful rnmine and then repeat the rnmine", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 65 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":65}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":66}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 66 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":66}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"do a rnmine without a cb","id":67}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":67,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"yTXlsM2o42hT46ao1/yHUQ==","expected":"yTXlsM2o42hT46ao1/yHUQ==","test":67,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":67,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":67}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":68}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 67 isOK: undefined : do a rnmine without a cb", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 68 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":68}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":69}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 69 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":69}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"rnMine - bad request bodies","id":70}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 70 isOK: undefined : rnMine - bad request bodies", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): INFO largerHash Got a rnmind request with either a rnMine - {"rnMine":" ","pkMine":"amTtRchMRWrHDXzDUNkO0w=="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a rnmind request with either a rnMine - {"rnMine":"{@#{$@#{$","pkMine":"WQyAGBMsqruv8xrSdratGQ=="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a rnmind request with either a rnMine - {"rnMine":"SSTFlXQHRWkS0015vAZ8uM0=","pkMine":"D9UQQHUXhobumedaZ1A1DA=="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a rnmind request with either a rnMine - {"rnMine":"6nA9pn22n6zI+1BG8owI","pkMine":"mHwuNJg2vRaNGt9/yHst6g=="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"i2YcxEA38JW/HPO9wT0yYA==","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"D03N2No3qYmvO+XGi6EYVw==","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"qxT9oSMGRghsrw9H8IDSmQ==","pkMine":"2VMuaOgicJzQ4s0HeLB2TIY="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"Wv4hiNH/7lt0499LHeZK4g==","pkMine":"4mX1tDWmNLNUoyM34zZt"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":" ","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":" ","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":" ","pkMine":"2VMuaOgicJzQ4s0HeLB2TIY="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":" ","pkMine":"4mX1tDWmNLNUoyM34zZt"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"{@#{$@#{$","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"{@#{$@#{$","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"{@#{$@#{$","pkMine":"2VMuaOgicJzQ4s0HeLB2TIY="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"{@#{$@#{$","pkMine":"4mX1tDWmNLNUoyM34zZt"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"SSTFlXQHRWkS0015vAZ8uM0=","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"SSTFlXQHRWkS0015vAZ8uM0=","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"SSTFlXQHRWkS0015vAZ8uM0=","pkMine":"2VMuaOgicJzQ4s0HeLB2TIY="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"SSTFlXQHRWkS0015vAZ8uM0=","pkMine":"4mX1tDWmNLNUoyM34zZt"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"6nA9pn22n6zI+1BG8owI","pkMine":" "}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"6nA9pn22n6zI+1BG8owI","pkMine":"{@#{$@#{$"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"6nA9pn22n6zI+1BG8owI","pkMine":"2VMuaOgicJzQ4s0HeLB2TIY="}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {"rnMine":"6nA9pn22n6zI+1BG8owI","pkMine":"4mX1tDWmNLNUoyM34zZt"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): INFO largerHash Got a /identity/rnmine request with a bum pkMine - {}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":18,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":22,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":23,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":24,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":25,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":26,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":28,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":29,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":33,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":37,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":38,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":39,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":40,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":41,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":43,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":44,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":48,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":"5k0uJATqKH/FaAmQepd57A==","expected":"5k0uJATqKH/FaAmQepd57A==","test":70,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":70}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":71}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 71 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":71}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":72}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 72 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/UdcCache:FPQuery( 1360): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1360): GC_CONCURRENT freed 2138K, 33% free 11606K/17224K, paused 3ms+4ms, total 36ms
,D/dalvikvm( 1360): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/jxcore-log( 3527): {"type":"end","test":72}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"do a cb and then a wrong peer and then finish with rnmine, make sure state didn't get lost","id":73}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"Ko/XyFNN175gRa8WOHVB7Q==","expected":true,"test":73,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":73,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"VVZKgjlxH9DY7E08xvsDLQ==","expected":"VVZKgjlxH9DY7E08xvsDLQ==","test":73,"type":"assert"}
I/jxcore-log( 3527): 
,D/ConnectivityService( 1015): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
I/ModemStatsDSDetect( 1288): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1288): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 0 by android.net.conn.INET_CONDITION_ACTION,icon color should be white.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/ModemStatsDSDetect( 1288): Inetcondition changed, blue->white
I/ModemStatsDSDetect( 1288): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[42,143,215,200,83,77,215,190,96,69,175,22,56,117,65,237],"expected":true,"test":73,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":51840,"expected":51840,"test":73,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":73}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":74}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 73 isOK: undefined : do a cb and then a wrong peer and then finish with rnmine, make sure state didn't get lost", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 74 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":74}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":75}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 75 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1015): sending alarm Alarm{43f41ab8 type 2 com.google.android.gms}
,I/jxcore-log( 3527): {"type":"end","test":75}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"do a cb and then a rnmine then a wrong peer then repeat rnmine to make sure state didn't get lost","id":76}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"z0b8Mdwedn8J5h2Kgfn9fQ==","expected":true,"test":76,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":76,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"sS6NO1uSwXxOg/oUtvZqmg==","expected":"sS6NO1uSwXxOg/oUtvZqmg==","test":76,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":76,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"sS6NO1uSwXxOg/oUtvZqmg==","expected":"sS6NO1uSwXxOg/oUtvZqmg==","test":76,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 76 isOK: undefined : do a cb and then a rnmine then a wrong peer then repeat rnmine to make sure state didn't get lost", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[207,70,252,49,220,30,118,127,9,230,29,138,129,249,253,125],"expected":true,"test":76,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":520512,"expected":520512,"test":76,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":76}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":77}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 77 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService( 1015): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1288): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1288): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1288): Inetcondition changed, white->blue
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1288): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/jxcore-log( 3527): {"type":"end","test":77}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":78}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 78 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":78}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"do a cb and then a rnmine with a rnmine that doesn't match the cb value","id":79}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":79,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"oK+3O68rwfkJvzLU7T+jsw==","expected":"oK+3O68rwfkJvzLU7T+jsw==","test":79,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":79}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":80}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 79 isOK: undefined : do a cb and then a rnmine with a rnmine that doesn't match the cb value", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 80 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1015): sending alarm Alarm{43ea44e0 type 3 android}
,I/jxcore-log( 3527): {"type":"end","test":80}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":81}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 81 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":81}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Make sure apis don't allow incorrect states","id":82}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event noIdentityExchange inappropriate in current state none","test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event waitForCb inappropriate in current state none","test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event waitForCb inappropriate in current state none","test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":"event waitForCb inappropriate in current state WaitForCb","test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":"event startListening inappropriate in current state WaitForCb","test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":5,"ok":true,"name":"should throw","operator":"throws","actual":"event waitForCb inappropriate in current state WaitForCb","test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":6,"ok":true,"name":"should throw","operator":"throws","actual":"event waitForCb inappropriate in current state WaitForCb","test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startListening inappropriate in current state WaitForCb","test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":8,"ok":true,"name":"should not be equal","operator":"notEqual","actual":[67,239,246,35,77,183,232,164,187,156,73,86,25,43,94,13],"test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":695488,"expected":695488,"test":82,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":82}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":83}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 82 isOK: undefined : Make sure apis don't allow incorrect states", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 83 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":83}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":84}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 84 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":84}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"test","name":"Make sure we can start, complete and then restart and complete, no state gets horked","id":85}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 85 isOK: undefined : Make sure we can start, complete and then restart and complete, no state gets horked", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":85}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":86}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 86 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":86}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":87}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 87 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7,
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
,I/jxcore-log( 3527): {"type":"end","test":87}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"multiplex can send data","id":88}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"String should be length:200","operator":"equal","actual":"eNDvBImeWUo8qdcJx6S59XuAHZ4fz2kAmo2rPlHKmmkxJws1tA7i6nrysQPDPnYJCbtmUuQZ4siiKqjpp9QwIaXkoFYZQD5XN6k0T3YBM9nzFvpVwQhHpo3iaxkFF5oeA18EjPLg5OWtHom55PLX6yB3tmpCR84LG72B6Tuwu0bkfmjgAJ8VVgNQWX0orGjJHuCu8uc0","expected":"eNDvBImeWUo8qdcJx6S59XuAHZ4fz2kAmo2rPlHKmmkxJws1tA7i6nrysQPDPnYJCbtmUuQZ4siiKqjpp9QwIaXkoFYZQD5XN6k0T3YBM9nzFvpVwQhHpo3iaxkFF5oeA18EjPLg5OWtHom55PLX6yB3tmpCR84LG72B6Tuwu0bkfmjgAJ8VVgNQWX0orGjJHuCu8uc0","test":88,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":88}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":89}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 88 isOK: undefined : multiplex can send data", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : String should be length:200", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 89 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":89}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":90}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 90 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":90}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"successfully create a new pkcs12 file and return hash value","id":91}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":91,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 91 isOK: undefined : successfully create a new pkcs12 file and return hash value", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"null","operator":"error","actual":null,"test":91,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":91,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"Ei/0/xqxDFrrZnXdDBziGQ==","expected":"Ei/0/xqxDFrrZnXdDBziGQ==","test":91,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":91}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":91,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":92}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : null", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 92 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":92}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":93}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 93 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":93}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"successfully read a previous pkcs12 file and return hash value","id":94}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":94,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":94,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should not throw","operator":"throws","test":94,"type":"assert"}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 94 isOK: undefined : successfully read a previous pkcs12 file and return hash value", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":94,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"aJyhh1T1ijHppkhzJOG5aA==","expected":"aJyhh1T1ijHppkhzJOG5aA==","test":94,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":94}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":95}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 95 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":95}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":96}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 96 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":96}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"failed to extract public key because of corrupt pkcs12 file","id":97}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"error thrown by extractPublicKey() function","expected":"error thrown by extractPublicKey() function","test":97,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":97}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":98}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 97 isOK: undefined : failed to extract public key because of corrupt pkcs12 file", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 98 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":98}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":99}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 99 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":99}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"failed to get mobile documents path","id":100}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"GetDocumentsPath error","expected":"GetDocumentsPath error","test":100,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":100}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":101}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 100 isOK: undefined : failed to get mobile documents path", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 101 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":101}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":102}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 102 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3527): {"type":"end","test":102}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#init should register the peerAvailabilityChanged event","id":103}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"12345","expected":"12345","test":103,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"foo","expected":"foo","test":103,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":true,"expected":true,"test":103,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":103}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":104}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 103 isOK: undefined : #init should register the peerAvailabilityChanged event", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 104 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":104}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":105}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 105 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3527): {"type":"end","test":105}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#init should register the networkChanged event","id":106}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":true,"expected":true,"test":106,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":106}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":107}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 106 isOK: undefined : #init should register the networkChanged event", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 107 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":107}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":108}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 108 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":108}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#startBroadcasting should throw on null device name","id":109}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"deviceName must be a string"},"test":109,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":109}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":110}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 109 isOK: undefined : #startBroadcasting should throw on null device name", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 110 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":110}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":111}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 111 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":111}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#startBroadcasting should throw on empty string device name","id":112}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"deviceName cannot be empty"},"test":112,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":112}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":113}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 112 isOK: undefined : #startBroadcasting should throw on empty string device name", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 113 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":113}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":114}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 114 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":114}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#startBroadcasting should throw on non-number port","id":115}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"port must be a number"},"test":115,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":115}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":116}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 115 isOK: undefined : #startBroadcasting should throw on non-number port", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 116 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":116}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":117}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 117 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":117}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#startBroadcasting should throw on NaN port","id":118}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"port must be a number"},"test":118,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":118}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":119}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 118 isOK: undefined : #startBroadcasting should throw on NaN port", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 119 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":119}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":120}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 120 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":120}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#startBroadcasting should throw on negative port","id":121}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"port must be greater than 0 and less than or equal 65536"},"test":121,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":121}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":122}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 121 isOK: undefined : #startBroadcasting should throw on negative port", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 122 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":122}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":123}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 123 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":123}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#startBroadcasting should throw on too large port","id":124}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"port must be greater than 0 and less than or equal 65536"},"test":124,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":124}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":125}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 124 isOK: undefined : #startBroadcasting should throw on too large port", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 125 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":125}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":126}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 126 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":126}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#startBroadcasting should call Mobile(\"StartBroadcasting\") without an error","id":127}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"foo","expected":"foo","test":127,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":9001,"expected":9001,"test":127,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","test":127,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":127}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":128}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 127 isOK: undefined : #startBroadcasting should call Mobile("StartBroadcasting") without an error", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 128 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":128}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":129}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 129 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":129}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","id":130}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"foo","expected":"foo","test":130,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":9001,"expected":9001,"test":130,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"fail","expected":"fail","test":130,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":130}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":131}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 130 isOK: undefined : #startBroadcasting should call Mobile("StartBroadcasting") and handle an error", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 131 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":131}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":132}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 132 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":132}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","id":133}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":133,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","test":133,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":133}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":134}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 133 isOK: undefined : #stopBroadcasting should call Mobile("StopBroadcasting") without an error", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1015): sending alarm Alarm{43ed53a8 type 3 android}
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 134 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":134}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":135}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 135 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":135}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#stopBroadcasting should call Mobile(\"StopBroadcasting\") and handle an error","id":136}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":136,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"fail","expected":"fail","test":136,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":136}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":137}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 136 isOK: undefined : #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 137 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":137}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":138}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 138 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":138}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#connect should call Mobile(\"Connect\") with a port and without an error","id":139}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":139,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":9001,"expected":9001,"test":139,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":139,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":139}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":140}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 139 isOK: undefined : #connect should call Mobile("Connect") with a port and without an error", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 140 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":140}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":141}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 141 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":141}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"#connect should call Mobile(\"Connect\") and handle an error","id":142}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":142,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"fail","expected":"fail","test":142,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":142}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":143}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 142 isOK: undefined : #connect should call Mobile("Connect") and handle an error", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 143 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1015): GC_CONCURRENT freed 1985K, 65% free 17958K/50212K, paused 19ms+9ms, total 108ms
,I/jxcore-log( 3527): {"type":"end","test":143}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":144}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 144 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3527): {"type":"end","test":144}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"should call Mobile(\"Disconnect\") without an error","id":145}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":145,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","test":145,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":145}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":146}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 145 isOK: undefined : should call Mobile("Disconnect") without an error", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 146 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":146}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"setup","id":147}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 147 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":147}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"should call Mobile(\"Disconnect\") and handle an error","id":148}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":148,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"fail","expected":"fail","test":148,"type":"assert"}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"end","test":148}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): {"type":"test","name":"teardown","id":149}
I/jxcore-log( 3527): 
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 148 isOK: undefined : should call Mobile("Disconnect") and handle an error", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback 149 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3527): {"type":"end","test":149}
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Total: 491	Passed: 491	Failed: 0
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@43e409c0 mBinding = false
,D/BluetoothManagerService( 1015): Message: 2
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothManagerService( 1015): Sending off request.
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
D/BluetoothAdapterState( 3573): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3573): Setting state to 13
I/BluetoothAdapterState( 3573): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3573): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 3573): onBluetoothDisable()
I/BluetoothAdapterState( 3573): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 3573): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3573): Scan Mode:21
D/BluetoothAdapterState( 3573): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 3573): bta_jv_rfcomm_stop_server
E/bt-btif ( 3573): bta_jv_rfcomm_stop_server
E/bt-btif ( 3573): bta_jv_rfcomm_stop_server
E/bt-btif ( 3573): bta_jv_rfcomm_stop_server
V/BluetoothFtpService:RfcommSocketAcceptThread( 3573): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3573): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3573): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3573): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3573): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothManagerService( 1015): Message: 60
D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3573): onReceive
,D/BluetoothMapService( 3573): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 3573): MAP Service closeService in
,D/btif_config_util( 3573): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
I/ActivityManager( 1015): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4624 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,I/BtOppRfcommListener( 3573): stopping Accept Thread
,I/BtOppRfcommListener( 3573): BluetoothSocket listen thread finished
,W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): ****TEST TOOK:  ms ****
I/jxcore-log( 3527): 
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/jxcore-log( 3527): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3527): 
,D/WifiStateMachine( 1015): handleMessage: E msg.what=131084
D/WifiStateMachine( 1015): processMsg: ConnectedState
D/WifiStateMachine( 1015): processMsg: L2ConnectedState
D/WifiStateMachine( 1015): processMsg: ConnectModeState
D/WifiStateMachine( 1015): processMsg: DriverStartedState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1015): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1015): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pService( 1015): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/TCMD    (  480): NL - Read 60 bytes from update socket.
I/chromium( 3527): [INFO:CONSOLE(63)] "logCallback Total: 491, Passed: 491, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
D/TCMD    (  480): NL - ignore NL message, type = 21
D/TCMD    (  480): Listening for incoming client connection request
,D/WifiStateMachine( 1015): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1015): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1015): connected time updated 250574
,D/WifiStateMachine( 1015): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1015): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1015): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1015): invokeExitMethods: DriverStartedState
,E/WifiStateMachine( 1015): Unexpected BatchedScanResults :OK
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1015): Attempting to switch to ETHERNET
D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1015): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1015): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1015): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131216
D/WifiStateMachine( 1015): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131216
D/WifiStateMachine( 1015): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1015): processMsg: SupplicantStartedState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
D/WifiP2pService( 1015): P2pDisablingState
D/WifiP2pService( 1015): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): p2p socket connection lost
D/WifiStateMachine( 1015): handleMessage: E msg.what=131205
D/WifiStateMachine( 1015): processMsg: WaitForP2pDisableState
,D/WifiP2pService( 1015): P2pDisabledState
D/WifiStateMachine( 1015): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1015): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1015): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1015): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1015): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1015): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1015): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1015): resetConnections(wlan0, 3)
D/NetUtils( 1015): android_net_utils_resetConnections in env=0x6122d250 clazz=0x6b500001 iface=wlan0 mask=0x3
,W/ContextImpl( 4624): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothPbapService( 3573): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/NativeCrypto( 1333): Read error: ssl=0x62e96be8: I/O error during system call, Connection timed out
,I/jxcore-log( 3527): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/CommandListener(  272): Clearing all IP addresses on wlan0
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
,D/BluetoothManagerService( 1015): Message: 20
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42897388:true
D/WifiStateMachine( 1015): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,V/NativeCrypto( 1333): SSL shutdown failed: ssl=0x62e96be8: I/O error during system call, Broken pipe
,W/bt-btif ( 3573): ag scb idx 1 not allocated
E/bt-btif ( 3573): BTA AG is already disabled, ignoring ...
I/bt_hwcfg( 3573): hw_epilog_process
W/bt-l2cap( 3573): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3573): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3573): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3573): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3573): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3573): L2CAP - PSM: 0x0017 not found for deregistration
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Checkin ( 1015): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiStateMachine( 1015): stopping supplicant
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
D/WifiStateMachine( 1015): setWifiState: disabling
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
,D/ConnectivityService( 1015): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiStateMachine( 1015): handleMessage: X
,I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
,W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
,I/ModemStatsDSDetect( 1288): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityService( 1015): Attempting to switch to mobile
D/ConnectivityService( 1015): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1015): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
W/XTWiFiOS( 1268): Active network info is not available
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1288): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1288): onReceive() - done, currentInetCondition=0
E/XTCC-3.0.0.2(  481): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  481): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/bt_hwcfg( 3573): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 3573): bt_hc_worker_thread exiting
D/bt_userial_mct( 3573): userial_close
I/bt_userial_mct( 3573): exiting userial_read_thread
,D/bt_userial_mct( 3573): Leaving userial_evt_read_thread()
,D/Nat464Xlat( 1015): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1288): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1288): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1288): onReceive() - done, currentInetCondition=0
E/XTCC-3.0.0.2(  481): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  481): [CSMgr] handleConnectivtyStatusChange failed
D/BluetoothManagerService( 1015): Message: 30
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 4624): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
,D/BluetoothManagerService( 1015): Message: 30
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
,I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
,W/ContextImpl( 4624): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/LocalBluetoothProfileManager( 4624): Adding local MAP profile
D/BluetoothMap( 4624): Create BluetoothMap proxy object
D/BluetoothManagerService( 1015): Message: 30
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
,W/ContextImpl( 4624): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/TCMD    (  480): NL - Read 68 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/wpa_supplicant( 3655): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  274): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  274):  STA Disconnected !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1015): handleMessage: E msg.what=147460
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/Tethering( 1015): InitialState.processMessage what=4
D/WifiStateMachine( 1015): handleMessage: E msg.what=147462
D/Tethering( 1015): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/WifiStateMachine( 1015): handleMessage: E msg.what=131101
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService( 1015): Message: 30
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
W/ContextImpl( 4624): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/LocalBluetoothProfileManager( 4624): LocalBluetoothProfileManager construction complete
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/DockEventReceiver( 4624): finishStartingService: stopping service
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/wpa_supplicant( 3655): eap_proxy Deinitialzed
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService( 1015): New client listening to asynchronous messages
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothInputDevice( 4624): Proxy object connected
D/HidProfile( 4624): Bluetooth service connected
D/BluetoothPan( 4624): BluetoothPAN Proxy object connected
D/PanProfile( 4624): Bluetooth service connected
D/BluetoothMap( 4624): Proxy object connected
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
D/MapProfile( 4624): Bluetooth service connected
V/BluetoothFtpReceiver( 3573): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMap( 4624): getConnectedDevices()
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothMap( 4624): Bluetooth is Not enabled
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/AuthorizationBluetoothService( 1333): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiStateMachine( 1015): handleMessage: E msg.what=196614
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
I/ActivityManager( 1015): Killing 3918:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
D/TCMD    (  480): Listening for incoming client connection request
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/wpa_supplicant( 3655): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274):  Wpa Supplicant Exiting !!
D/MDMCTBK (  274): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
D/WifiStateMachine( 1015): handleMessage: E msg.what=147458
D/WifiStateMachine( 1015): processMsg: SupplicantStoppingState
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
D/WifiStateMachine( 1015): Supplicant connection lost
D/MDMCTBK (  274): wifi_close_sockets: Exit
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
D/BTSNOOP-DISP( 3573): btsnoop_close
I/bt_vendor( 3573): cleanup
I/bt_hwcfg( 3573): Starting hciattach daemon
I/bt_hwcfg( 3573): try to set false
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/GKI_LINUX( 3573): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3573): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 3573): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothAdapterState( 3573): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/HeadsetService( 3573): Received stop request...Stopping profile...
D/BluetoothHeadset( 1243): Proxy object disconnected
D/BluetoothHeadset( 1243): Proxy object disconnected
D/BluetoothHeadset( 1243): Proxy object disconnected
D/BluetoothHeadset( 1015): Proxy object disconnected
D/A2dpService( 3573): Received stop request...Stopping profile...
D/A2dpStateMachine( 3573): Exit Disconnected: -1
D/BluetoothAdapterState( 3573): Stopping profile services that were post enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
D/BluetoothA2dp( 1015): Proxy object disconnected
D/HidService( 3573): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4624): Proxy object disconnected
D/HidProfile( 4624): Bluetooth service disconnected
D/BluetoothAdapterService( 3573): Profile still running: com.android.bluetooth.hdp.HealthService
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
W/BluetoothHeadsetServiceJni( 3573): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3573): Cleaning up Bluetooth Handsfree callback object
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/HealthService( 3573): Received stop request...Stopping profile...
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/PanService( 3573): Received stop request...Stopping profile...
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothTethering( 1015): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1015): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1015): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43e09ba8
D/BluetoothTethering( 1015): got CMD_CHANNEL_DISCONNECTED
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
D/BluetoothPan( 4624): BluetoothPAN Proxy object disconnected
D/PanProfile( 4624): Bluetooth service disconnected
D/BluetoothPan( 1015): BluetoothPAN Proxy object disconnected
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BtGatt.DebugUtils( 3573): handleDebugAction() action=null
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BtGatt.GattService( 3573): Received stop request...Stopping profile...
D/BtGatt.GattService( 3573): stop()
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/BluetoothMapService( 3573): Received stop request...Stopping profile...
D/BluetoothMapService( 3573): stop()
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMapService( 3573): MAP Service closeService in
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
D/BluetoothAdapterService( 3573): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 3573): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3573): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3573): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService( 3573): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3573): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3573): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3573): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3573): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3573): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3573): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 3573): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3573): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3573): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 3573): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3573): cleanup()
D/BluetoothMapService( 3573): MAP Service closeService in
D/BluetoothAdapterState( 3573): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3573): Setting state to 10
I/BluetoothAdapterState( 3573): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3573): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 3573): Entering OffState
D/BluetoothManagerService( 1015): Message: 60
D/BluetoothManagerService( 1015): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1015): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothPbap( 4624): onBluetoothStateChange: up=false
D/WifiStateMachine( 1015): setWifiState: disabled
D/BluetoothHeadset( 1243): onBluetoothStateChange: up=false
D/WifiStateMachine( 1015): transitionTo: destState=InitialState
D/WifiStateMachine( 1015): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1015): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1015): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1015): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1015): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1015): invokeEnterMethods: InitialState
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1268): No entry in secure settings for enhanced location services: false
D/BluetoothHeadset( 1243): onBluetoothStateChange: up=false
W/XTWiFiOS( 1268): Active network info is not available
E/XTCC-3.0.0.2(  481): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  481): [WwanPosMgr] handleConnectivtyStatusChange failed
D/BluetoothHeadset( 1243): onBluetoothStateChange: up=false
D/BluetoothMap( 4624): onBluetoothStateChange: up=false
E/XTCC-3.0.0.2(  481): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  481): [CSMgr] handleConnectivtyStatusChange failed
W/Settings( 4038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothMap( 4624): Proxy object disconnected
D/MapProfile( 4624): Bluetooth service disconnected
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
W/Settin,gs( 1208): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothPan( 4624): onBluetoothStateChange on: false
D/BluetoothPan( 1015): onBluetoothStateChange on: false
D/BluetoothInputDevice( 4624): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1015): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1015): onBluetoothStateChange: up=false
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService( 1015): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@43e409c0 mBinding = false
D/BluetoothManagerService( 1015): Sending unbind request.
D/BluetoothManagerService( 1015): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapter( 1081): 1109464856: getState() :  mService = null. Returning STATE_OFF
D/AndroidRuntime( 4657): 
D/AndroidRuntime( 4657): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BluetoothAdapterService( 3573): Cleaning up adapter native....
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
D/AndroidRuntime( 4657): CheckJNI is OFF
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
,W/ContextImpl( 4624): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapter( 1208): 1111134008: getState() :  mService = null. Returning STATE_OFF
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
D/BluetoothAdapter( 1208): 1111134008: getState() :  mService = null. Returning STATE_OFF
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
D/DockEventReceiver( 4624): finishStartingService: stopping service
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3527): 
I/GKI_LINUX( 3573): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3573): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 3573): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3573): cleanupNative: return from cleanup
D/BluetoothAdapterService( 3573): Done cleaning up adapter native....
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothAdapterService(1107990088)( 3573): ****onDestroy()********
D/BtGatt.GattService( 3573): cleanup()
W/bt-btif ( 3573): GATTC Module not enabled/already disabled
W/bt-btif ( 3573): GATTS Module not enabled/already disabled
D/dalvikvm( 4657): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4657): Added shared lib libjavacore.so 0x0
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/BluetoothAdapter( 4624): 1108028168: getState() :  mService = null. Returning STATE_OFF
D/dalvikvm( 4657): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4657): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4657): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
V/BluetoothFtpReceiver( 3573): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3573): BluetoothFtpReceiver Stop Service
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
V/BluetoothFtpService( 3573): Ftp Service onDestroy
V/BluetoothFtpService( 3573): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3573): Shutdown
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
,D/AuthorizationBluetoothService( 1333): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager( 1015): Killing 3889:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4670 uid=10016 gids={50016, 3002}
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
I/jxcore-log( 3527): The client has disconnected!
I/jxcore-log( 3527): 
I/jxcore-log( 3527): Turning radios to false
I/jxcore-log( 3527): 
D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3527): toggleBluetooth - 
I/jxcore-log( 3527): 
D/WifiService( 1015): setWifiEnabled: false pid=3527, uid=10380
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3527): toggleWiFi
I/jxcore-log( 3527): 
,D/dalvikvm( 4657): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/Checkin ( 4670): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
I/ActivityManager( 1015): Killing 4038:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,E/memtrack( 4657): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4657): failed to load memtrack module: -2
,D/AndroidRuntime( 4657): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10380 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 3527:com.test.thalitest/u0a380 (adj 9): stop com.test.thalitest
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{4486caa8 u0 com.test.thalitest/.MainActivity t3}
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/NetlinkEvent(  272): Unexpected netlink message. type=0x11
W/Netd    (  272): No subsystem found in netlink event
D/TCMD    (  480): NL - Read 444 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 17
D/TCMD    (  480): Listening for incoming client connection request
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  274): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/WindowState( 1015): WIN DEATH: Window{43807b58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1015): Client connection lost with reason: 4
,D/TCMD    (  480): NL - Read 1000 bytes from update socket.
D/TCMD    (  480): NL - message type is RTM_NEWLINK
,D/TCMD    (  480): Listening for incoming client connection request
W/PackageSettings( 1015): Skipping PackageSetting{4239f2b8 com.example.hello/10378} due to missing metadata
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10380 user=0: pkg removed
,D/dalvikvm( 3433): GC_FOR_ALLOC freed 36K, 5% free 18195K/19004K, paused 11ms, total 13ms
,D/TCMD    (  480): NL - Read 444 bytes from update socket.
D/TCMD    (  480): NL - ignore NL message, type = 17
D/TCMD    (  480): Listening for incoming client connection request
,D/NetlinkEvent(  272): Unexpected netlink message. type=0x11
W/Netd    (  272): No subsystem found in netlink event
I/MDMCTBK (  274): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  274): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  274): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  274): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  274): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/dalvikvm( 2130): GC_EXPLICIT freed 6042K, 44% free 9753K/17224K, paused 2ms+6ms, total 42ms
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,W/GeofencerStateMachine( 1208): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/VoicemailCleanupService( 4070): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,D/dalvikvm( 2167): GC_EXPLICIT freed 2827K, 42% free 10048K/17224K, paused 10ms+5ms, total 116ms
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
D/dalvikvm( 1015): GC_EXPLICIT freed 1461K, 65% free 17927K/50184K, paused 4ms+12ms, total 116ms
D/dalvikvm( 1302): GC_EXPLICIT freed 2792K, 33% free 11594K/17224K, paused 39ms+5ms, total 135ms
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/Launcher( 1302): Deferring update until onResume
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447842562
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/InternalIcingCorporaPro( 2167): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1015): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4705 uid=10059 gids={50059, 3003, 1028, 1015}
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447842562
,I/Launcher( 1302): Deferring update until onResume
,I/InternalIcingCorporaPro( 2167): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1015): removePackageParticipantsLocked: uid=10380 #1
,D/dalvikvm( 1015): GC_EXPLICIT freed 450K, 65% free 17915K/50184K, paused 9ms+14ms, total 221ms
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/AndroidRuntime( 4657): Shutting down VM
,D/dalvikvm( 4657): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,W/ActiveOrDefaultContextProvider( 4705): Missing scope.enter somewhere. Returning default context
,I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4723 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/GAV2    ( 4705): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 4723): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/MDMCTBK (  274): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  274): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
,I/MDMCTBK (  274): checkDefaultInst, pid match
I/dalvikvm( 4106): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4106): VFY: unable to resolve virtual method 338: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 4106): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1360): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1360): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1360): Loading module com.google.android.gms.games from APK com.google.android.gms
,E/NetworkScheduler.SchedulerReceiver( 1333): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1333): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131208
D/WifiStateMachine( 1015): processMsg: InitialState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131208
D/WifiStateMachine( 1015): processMsg: InitialState
D/WifiStateMachine( 1015): processMsg: DefaultState
D/WifiStateMachine( 1015): handleMessage: X
D/WifiStateMachine( 1015): handleMessage: E msg.what=131208
D/WifiStateMachine( 1015): processMsg: InitialState
D/WifiStateMachine( 1015): processMsg: DefaultState
,D/WifiStateMachine( 1015): handleMessage: X
,I/LocationSettingsChecker( 1360): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager( 1015): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4746 uid=10058 gids={50058}
,D/Checkin ( 2130): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/gH_CompatibleDatabase( 1360): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1360): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1360): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1360): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1360): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1360): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1360): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1360): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,I/PeopleContactsSync( 1360): CP2 sync disabled
,D/gH_CompatibleDatabase( 1360): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,I/Icing   ( 1360): doRemovePackageData com.test.thalitest
,D/gH_CompatibleDatabase( 1360): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1360): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1360): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1360): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1015): Killing 4141:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/SQLiteLog( 2130): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 2130): Error inserting state=an=null au=null avc=-1 avn=null name=com.test.thalitest st=2 timestamp=1447842562125 timezone=3600 name=PackageInfoTrigger
E/SQLiteDatabase( 2130): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2130): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2130): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2130): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2130): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 2130): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,E/SQLiteDatabase( 2130): Error inserting state=event=am_kill pid=4141 process=android.process.media reason=empty+%239 selectadj=15 timestamp=1447842562844 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2130): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2130): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2130): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2130): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2130): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Documents( 4746): Loading roots for com.android.providers.downloads.documents
,E/SQLiteDatabase( 4746): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4746): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4746): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4746): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4746): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4746): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4746): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4746): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4746): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4746): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4746): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4746): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 4746): Shutting down VM
,W/dalvikvm( 4746): threadid=1: thread exiting with uncaught exception (group=0x417cdd40)
I/ActivityManager( 1015): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4773 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1015): Killing 4624:com.android.settings/1000 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/AndroidRuntime( 4746): FATAL EXCEPTION: main
E/AndroidRuntime( 4746): Process: com.android.documentsui, PID: 4746
E/AndroidRuntime( 4746): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4746): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4746): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4746): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4746): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4746): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4746): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4746): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4746): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4746): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4746): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4746): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4746): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4746): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4746): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4746): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4746): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4746): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4746): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4746): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4746): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4746): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4746): 	... 10 more
,E/SQLiteLog( 2130): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,D/WifiService( 1015): Client connection lost with reason: 4
,E/SQLiteDatabase( 2130): Error inserting state=event=am_kill pid=4624 process=com.android.settings reason=empty+%239 selectadj=15 timestamp=1447842562894 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2130): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2130): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2130): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2130): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2130): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1015): Killing 3573:com.android.bluetooth/1002 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  276): GC_EXPLICIT freed 44K, 48% free 9012K/17224K, paused 1ms+3ms, total 22ms
E/SQLiteLog( 2130): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
I/Process ( 4746): Sending signal. PID: 4746 SIG: 9
,E/SQLiteDatabase( 2130): Error inserting state=event=am_kill pid=3573 process=com.android.bluetooth reason=empty+%239 selectadj=15 timestamp=1447842562909 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2130): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2130): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2130): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2130): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2130): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2130): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2130): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1015): Can't write: system_app_crash
E/DropBoxManagerService( 1015): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1015): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1015): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1015): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1015): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1015): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1015): 	... 5 more
,I/ActivityManager( 1015): Process com.android.documentsui (pid 4746) has died.
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms

```
