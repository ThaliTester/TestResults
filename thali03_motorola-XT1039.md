#### Test 52320939cae1769_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of /dev/log/system
W/SocketClient(  271): write error (Broken pipe)
D/AndroidRuntime( 3545): 
D/AndroidRuntime( 3545): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3545): CheckJNI is OFF
D/dalvikvm( 3545): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3545): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3545): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3545): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3545): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3545): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3545): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3545): failed to load memtrack module: -2
D/AndroidRuntime( 3545): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3545
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3561 uid=10421 gids={50421, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3545): Shutting down VM
D/dalvikvm( 3545): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3561): Binding Chromium to main looper Looper (main, tid 1) {41f2aa00}
I/LibraryLoader( 3561): Expected native library version number "",actual native library version number ""
I/chromium( 3561): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3561): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43cf7f18:true
D/BluetoothAdapter( 3561): 1106505744: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3561): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3561): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3561): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3561): Local Branch: 
I/Adreno-EGL( 3561): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3561): Local Patches: NONE
I/Adreno-EGL( 3561): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3561): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3561): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3561): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3561): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3561): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3561): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3561): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3561): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3561): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3561): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3561): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3561): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3561): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3561): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3561): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3561): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3561): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3561): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3561): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3561): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3561): Enabling debug mode 0
,W/AwContents( 3561): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3561): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,399
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +371ms (total +399ms)
,D/JsMessageQueue( 3561): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3561): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f2eeb0
,D/dalvikvm( 3561): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f2eeb0
,D/jxcore_app_log( 3561): JniHelper::setJavaVM(0x41577fa8), pthread_self() = 1613857176
,D/JX-Cordova( 3561): jxcore cordova android initializing
,I/dalvikvm( 3561): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 3561): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3561): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3561): GC_CONCURRENT freed 2778K, 17% free 14412K/17224K, paused 3ms+11ms, total 52ms
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 237K, 17% free 14372K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 178K, 17% free 14412K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3561): Grow heap (frag case) to 16.248MB for 146998-byte allocation
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 269K, 17% free 14449K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3561): Grow heap (frag case) to 16.353MB for 220492-byte allocation
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 379K, 18% free 14519K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3561): Grow heap (frag case) to 16.527MB for 330734-byte allocation
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 576K, 19% free 14642K/17908K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3561): Grow heap (frag case) to 16.805MB for 496096-byte allocation
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 879K, 20% free 14822K/18396K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3561): Grow heap (frag case) to 17.216MB for 744140-byte allocation
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 1302K, 22% free 15083K/19124K, paused 27ms, total 27ms
,D/dalvikvm( 3561): GC_CONCURRENT freed 1672K, 20% free 15458K/19124K, paused 1ms+3ms, total 31ms
,D/dalvikvm( 3561): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 400K, 20% free 15420K/19124K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3561): Grow heap (frag case) to 18.688MB for 1674304-byte allocation
,D/dalvikvm( 3561): GC_CONCURRENT freed 1704K, 23% free 15994K/20760K, paused 1ms+3ms, total 32ms
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 1396K, 23% free 16082K/20760K, paused 30ms, total 32ms
,I/dalvikvm-heap( 3561): Grow heap (frag case) to 20.133MB for 2511452-byte allocation
,D/dalvikvm( 3561): GC_CONCURRENT freed 331K, 21% free 18410K/23216K, paused 5ms+5ms, total 48ms
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 4338K, 27% free 17059K/23216K, paused 36ms, total 36ms
,I/dalvikvm-heap( 3561): Grow heap (frag case) to 22.285MB for 3767174-byte allocation
,D/dalvikvm( 3561): GC_CONCURRENT freed 247K, 24% free 20636K/26896K, paused 5ms+5ms, total 47ms
,D/dalvikvm( 3561): GC_FOR_ALLOC freed 3119K, 33% free 18020K/26896K, paused 28ms, total 28ms
,W/jxcore-log( 3561): Initializing JXcore engine
,W/jxcore-log( 3561): JXcore engine is ready
,D/dalvikvm( 3561): GC_CONCURRENT freed 347K, 24% free 20657K/26896K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 3561): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 3561): Starting JXcore engine
,W/jxcore-log( 3561): Platform android
W/jxcore-log( 3561): 
,W/jxcore-log( 3561): Process ARCH arm
W/jxcore-log( 3561): 
,I/jxcore-log( 3561): JXcore Cordova bridge is ready!
I/jxcore-log( 3561): 
,W/jxcore-log( 3561): JXcore engine is started
,I/chromium( 3561): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3561): Toggling radios to true
I/jxcore-log( 3561): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): enable():  mBluetooth =null mBinding = false
,W/Settings( 1242): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothManagerService( 1019): Message: 1
,D/BluetoothManagerService( 1019): MESSAGE_ENABLE: mBluetooth = null
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1261): Active network info is not available
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3607 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/Settings( 1242): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=3561, uid=10421
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 23ms
,W/Settings( 1242): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1261): Active network info is not available
,W/Settings( 1242): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiStateMachine( 1019): setting operational mode to 1
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 4ms+2ms, total 25ms
,I/jxcore-log( 3561): Radios toggled
I/jxcore-log( 3561): 
,D/AdapterServiceConfig( 3607): Adding HeadsetService
D/AdapterServiceConfig( 3607): Adding A2dpService
D/AdapterServiceConfig( 3607): Adding HidService
D/AdapterServiceConfig( 3607): Adding HealthService
D/AdapterServiceConfig( 3607): Adding PanService
D/AdapterServiceConfig( 3607): Adding GattService
,D/AdapterServiceConfig( 3607): Adding BluetoothMapService
,D/BluetoothAdapterService( 3607): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothAdapterState( 3607): make
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4462c0f8:true
,I/bluedroid( 3607): init
,I/BluetoothAdapterState( 3607): Entering OffState
,I/bte_conf( 3607): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3607): get_profile_interface socket
I/GKI_LINUX( 3607): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1019): Message: 40
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 3607): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothAdapterProperties( 3607): Name is: XT1039
D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
I/bluedroid( 3607): config_hci_snoop_log
,D/BluetoothManagerService( 1019): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/dalvikvm( 1199): GC_EXPLICIT freed 1357K, 41% free 10256K/17224K, paused 3ms+6ms, total 38ms
D/BluetoothAdapterState( 3607): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3607): Setting state to 11
I/BluetoothAdapterState( 3607): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3607): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3607): make
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3645 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/BluetoothHeadset( 1019): Proxy object connected
,D/BluetoothHeadset( 1231): Proxy object connected
D/BluetoothHeadset( 1231): Proxy object connected
,D/BluetoothHeadset( 1231): Proxy object connected
D/HeadsetService( 3607): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3607): classInitNative: succeeds
D/HeadsetStateMachine( 3607): Version 1.6
,D/HeadsetStateMachine( 3607): make
,I/BluetoothAdapterState( 3607): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3607): get_profile_interface handsfree
,D/BluetoothA2dp( 1019): Proxy object connected
,D/A2dpService( 3607): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3607): classInitNative: succeeds
V/Avrcp   ( 3607): make
,I/bluedroid( 3607): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3607): classInitNative: succeeds
,D/A2dpStateMachine( 3607): make
,I/bluedroid( 3607): get_profile_interface a2dp
,I/GKI_LINUX( 3607): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3607): warning : no command pending, ignore ack
D/A2dpStateMachine( 3607): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3607): classInitNative: succeeds
D/HidService( 3607): Received start request. Starting profile...
,I/bluedroid( 3607): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3607): classInitNative: succeeds
,D/HealthService( 3607): Received start request. Starting profile...
I/bluedroid( 3607): get_profile_interface health
,I/BluetoothPanServiceJni( 3607): classInitNative(L105): succeeds
E/DataBuffer( 1199): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4215e428)
,D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
D/PanService( 3607): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3607): initializeNative(L110): pan
,I/bluedroid( 3607): get_profile_interface pan
D/BluetoothTethering( 1019): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothTethering( 1019): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43c3db90
,I/BtGatt.JNI( 3607): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3607): handleDebugAction() action=null
D/BtGatt.GattService( 3607): Received start request. Starting profile...
D/BtGatt.GattService( 3607): start()
,I/bluedroid( 3607): get_profile_interface gatt
,I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  273): NetlinkHandler, interfaceAdded
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
E/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  273): , Wifi = 0
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =0, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=0,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
,I/MDMCTBK (  273): setSarCtrl:set SAR over QMI, conn:0, ep:0,wf:0, mf:0, chrg:1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/TCMD    (  387): NL - Read 1004 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1019): InitialState.processMessage what=4
I/MDMCTBK (  273): send SAR ctrl over QMI
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  273): NetlinkHandler, interfaceAdded
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
E/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  273): , Wifi = 0
I/MDMCTBK (  273): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/BluetoothMapService( 3607): Received start request. Starting profile...
,D/BluetoothMapService( 3607): start()
D/TCMD    (  387): NL - Read 1004 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/HeadsetPhoneState( 3607): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3607): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3607): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3607): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3607): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3607): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3607): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/HeadsetPhoneState( 3607): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3607): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/QsoftapCmd(  271): Got softap fwreload command we are passing on
,D/SoftapController(  271): Softap fwReload - Ok
D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring down wlan0
D/BluetoothAdapterState( 3607): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3607): enable
,I/bt_hci_bdroid( 3607): init
I/bt_vendor( 3607): bt-vendor : init
I/bt_hci_bdroid( 3607): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3607): userial_init
I/bt_hwcfg( 3607): Starting hciattach daemon
I/bt_hwcfg( 3607): try to set false
I/bt_hwcfg( 3607): Starting hciattach daemon
,I/bt_hwcfg( 3607): try to set true
,I/bt_hci_bdroid( 3607): bt_hc_worker_thread started
,I/qcom-bluetooth( 3674): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,D/WifiStateMachine( 1019): setWifiState: enabling
,I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1261): Active network info is not available
,I/qcom-bluetooth( 3682): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3683): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/ActivityManager( 1019): Killing 3286:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/wpa_supplicant( 3679): Successfully initialized wpa_supplicant
I/qcom-bluetooth( 3685): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/wpa_supplicant( 3679): rfkill: Cannot open RFKILL control device
D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
I/qcom-bluetooth( 3686): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 3687): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
I/rmt_storage(  349): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb73e21d0
I/rmt_storage(  349): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  349): wakelock acquired: 1, error no: 42
I/rmt_storage(  349): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220664776)
,E/Diag_Lib( 3689): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3689): Setting internal use port to rmnet0
E/Diag_Lib( 3689):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3689): Failed on DIAG init
E/Diag_Lib( 3689): linux_qmi_qmux_if_client_get_proc_name: pid=3689, proc_name=hci_qcomm_init
E/Diag_Lib( 3689): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3689): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3689): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3689): qmi_client [3689]: successfully connected to server, attempt=1
E/Diag_Lib( 3689): linux_qmi_qmux_if_client_get_client_id [3689]: qmux_client_id=13
E/Diag_Lib( 3689): qmi_client [3689] 13: qmux_client ID is initialized
E/Diag_Lib( 3689): qmi_client [3689] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3689): qmi_client [3689] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3689): qmi_client [3689] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3689): Sending signal ...... to read cmd data 
E/Diag_Lib( 3689): qmi error code.........:0
E/Diag_Lib( 3689): qmi sys error code.........:0
E/Diag_Lib( 3689): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3689): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3689): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3689): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3689): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3689): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3689): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3689): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3689): qmi_init:  Created client handle b8589788
,E/Diag_Lib( 3689): qmi_client [3689] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3689): qmi_client [3689] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3689): Sending signal ...... to read cmd data 
E/Diag_Lib( 3689): qmi error code.........:0
,E/Diag_Lib( 3689): qmi sys error code.........:0
E/Diag_Lib( 3689): Setting the api flag to : 1
,E/Diag_Lib( 3689): qmi_client [3689] 13: sending 54 bytes on fd = 8
,D/WifiService( 1019): New client listening to asynchronous messages
E/Diag_Lib( 3689): qmi_client [3689] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3689):  API Flag .............. 1 
E/Diag_Lib( 3689):  Message ID ............... 92 
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
E/Diag_Lib( 3679): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3679): Setting internal use port to rmnet0
,D/AuthorizationBluetoothService( 1343): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/wpa_supplicant( 3679): baseband property is set to [msm]
E/Diag_Lib( 3689): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3689): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3689): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3689): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3689): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3689): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3689): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3689): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3689): qmi_client [3689] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3689): qmi_client [3689] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3689): Sending signal ...... to read cmd data 
E/Diag_Lib( 3689): qmi error code.........:0
E/Diag_Lib( 3689): qmi sys error code.........:0
E/Diag_Lib( 3689): qmi_release: Released client handle ff
E/Diag_Lib( 3689): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3689): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3689): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3689): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3689): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3689): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3689): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3689): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3689): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3689): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3689): qmi_client [3689] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3689): qmi_client [3689] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3689): Sending signal ...... to read cmd data 
E/Diag_Lib( 3689): qmi error code.........:0
E/Diag_Lib( 3689): qmi sys error code.........:0
E/Diag_Lib( 3689): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3689] 13
E/Diag_Lib( 3689): qmi_client [3689] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3689): qmi_client [3689] 13: failed to locate client data
E/Diag_Lib( 3689): qmi_client [3689] 13: calling release of fd=8
E/Diag_Lib( 3689): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
E/wpa_supplicant( 3679):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3679): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3679): card_info[i].card_state: 0x2
E/wpa_supplicant( 3679): card_info[i].error_code: 0x3
E/wpa_supplicant( 3679): SIM/USIM not ready
,E/wpa_supplicant( 3679): Error while reading SIM card status
,E/wpa_supplicant( 3679): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3679): card_info[i].card_state: 0x2
E/wpa_supplicant( 3679): card_info[i].error_code: 0x3
E/wpa_supplicant( 3679): SIM/USIM not ready
,I/wpa_supplicant( 3679): eap_proxy: Card not ready
,I/rmt_storage(  349): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  349): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  349): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220664776) wakelock released: 1, error no: 0
I/rmt_storage(  349): 
,I/rmt_storage(  349): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb73e21d0
,D/Checkin ( 2178): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2178): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/wpa_supplicant( 3679): Long line in configuration file truncated
,I/wpa_supplicant( 3679): rfkill: Cannot open RFKILL control device
D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/qcom-bluetooth( 3694): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3695): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3607): bluetooth satus is on
I/GKI_LINUX( 3607): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3607): btu_task pending for preload complete event
,D/bt_userial_mct( 3607): userial_open(port:0)
I/bt_userial_vendor( 3607): Done intiailizing UART
I/bt_userial_vendor( 3607): Done intiailizing UART
,I/bt_userial_mct( 3607): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3607): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 3607): Entering userial_read_thread()
,I/bt-btu  ( 3607): btu_task received preload complete event
I/        ( 3607): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3607): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3607): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3607): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3607): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3607): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3607): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3607): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3607): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3607): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3607): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3607): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3607): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3607): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3607): BTE_InitTraceLevels -- TRC_BTIF
,E/wpa_supplicant( 3679): COUNTRY Code Recived
E/wpa_supplicant( 3679): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3679): baseband property is set to [msm]
,E/wpa_supplicant( 3679):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3679): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3679): card_info[i].card_state: 0x2
E/wpa_supplicant( 3679): card_info[i].error_code: 0x3
E/wpa_supplicant( 3679): SIM/USIM not ready
,E/wpa_supplicant( 3679): Error while reading SIM card status
E/wpa_supplicant( 3679): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3679): card_info[i].card_state: 0x2
E/wpa_supplicant( 3679): card_info[i].error_code: 0x3
E/wpa_supplicant( 3679): SIM/USIM not ready
,I/wpa_supplicant( 3679): eap_proxy: Card not ready
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1261): Active network info is not available
E/bt-btm  ( 3607): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f0b9049 
,E/bt-btm  ( 3607): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f0b9049 
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
E/bt-btif ( 3607): Calling BTA_HhEnable
E/bt-btif ( 3607): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3607): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3607): Name is: XT1039
,I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3607): Scan Mode:21
I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothAdapterProperties( 3607): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:8 len:6
,D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
,D/BluetoothAdapterProperties( 3607): Adding bonded device:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 3607): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/bte_conf( 3607): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/wpa_supplicant( 3679): COUNTRY Code Recived -COUNTRY PL
I/bte_conf( 3607): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3607): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3607): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,E/bt_mct  ( 3607): hci lib postload completed
,D/BluetoothPanServiceJni( 3607): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 3607): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3607): ScanMode =  21
D/BluetoothAdapterProperties( 3607): State =  11
D/BluetoothAdapterProperties( 3607): Setting state to 12
I/BluetoothAdapterState( 3607): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3607): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan( 1019): onBluetoothStateChange on: true
D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/BluetoothHeadset( 1231): onBluetoothStateChange: up=true
I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3607): Discoverable Timeout:120
D/BluetoothHeadset( 1231): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3607): Entering On State
D/BluetoothHeadset( 1231): onBluetoothStateChange: up=true
D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/BluetoothHeadset( 1019): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 11 -> 12
,D/WifiStateMachine( 1019): setDetailed state, old =IDLE and new state=DISCONNECTED
,D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
E/wpa_supplicant( 3679): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3679): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/BluetoothManagerService( 1019): Message: 40
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3607): onReceive
,D/BluetoothMapService( 3607): STATE_ON
,D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
D/BluetoothMapService( 3607): Map Service startRfcommSocketListener
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring up p2p0
I/qcom-bt-wlan-coex( 3709): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothMapService( 3607): Map Service initSocket
,D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
W/BluetoothAdapter( 3607): getBluetoothService() called with no BluetoothManagerCallback
D/WifiStateMachine( 1019): handleMessage: X
E/BluetoothServiceJni( 3607): SOCK FLAG = 1 ***********************
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set country code PL
I/BluetoothAdapterProperties( 3607): adapterPropertyChangedCallback with type:7 len:4
E/wpa_supplicant( 3679): COUNTRY Code Recived
E/wpa_supplicant( 3679): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set frequency band 2
D/BluetoothMapService( 3607): Accepting socket connection...
D/BluetoothAdapterProperties( 3607): Scan Mode:21
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1019): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
W/ContextImpl( 3645): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService( 1019): MCC mode enabled 0
D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-21ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-21ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-23ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-23ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3679): COUNTRY Code Recived
,E/wpa_supplicant( 3679): COUNTRY Code Recived
D/WifiP2pService( 1019): InactiveState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothPbapService( 3607): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothPbapService( 3607): Handler(): got msg=1
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@438eaf40:true
W/BluetoothAdapter( 3607): getBluetoothService() called with no BluetoothManagerCallback
D/Checkin ( 2178): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/BluetoothServiceJni( 3607): SOCK FLAG = 1 ***********************
,D/Checkin ( 2178): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/LocalBluetoothProfileManager( 3645): Adding local A2DP profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3645): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3645): Adding local HEADSET profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3645): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3645): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3645): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3645): Adding local MAP profile
D/BluetoothMap( 3645): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3645): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3645): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3645): LocalBluetoothProfileManager construction complete
,D/dalvikvm( 1019): GC_EXPLICIT freed 22446K, 65% free 17830K/50100K, paused 4ms+11ms, total 139ms
,D/DockEventReceiver( 3645): finishStartingService: stopping service
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothA2dp( 3645): Proxy object connected
,D/A2dpProfile( 3645): Bluetooth service connected
,D/BluetoothHeadset( 3645): Proxy object connected
,D/HeadsetProfile( 3645): Bluetooth service connected
D/BluetoothInputDevice( 3645): Proxy object connected
,D/HidProfile( 3645): Bluetooth service connected
,D/BluetoothPan( 3645): BluetoothPAN Proxy object connected
D/PanProfile( 3645): Bluetooth service connected
D/BluetoothMap( 3645): Proxy object connected
D/MapProfile( 3645): Bluetooth service connected
,D/BluetoothMap( 3645): getConnectedDevices()
D/BluetoothPbap( 3645): Proxy object connected
,D/PbapServerProfile( 3645): Bluetooth service connected
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/AuthorizationBluetoothService( 1343): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothAdapter( 3607): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3607): SOCK FLAG = 0 ***********************
I/BtOppRfcommListener( 3607): Accept thread started.
,E/AuthorizationBluetoothService( 1343): Proximity feature is not enabled.
,V/BluetoothFtpService( 3607): Ftp Service onCreate
I/BluetoothFtpService( 3607): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3607): Starting FTP service
V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3607): Handler(): got msg=1
V/BluetoothFtpService( 3607): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3607): Ftp Service initSocket
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3607): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3607): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3607): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3607): Run Accept thread
,D/Checkin ( 2178): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  273): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): wifi_connect_to_supplicant, current pid is = 273
D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  273): wifi_close_sockets: Exit
,E/MDMCTBK (  273): Attach monitor thread
I/MDMCTBK (  273): createWifiMonitorThread: Started the wifi monitor thread -1202130168
,D/MDMCTBK (  273): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2178): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 06:7c:34:11:b3:cb
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 06:7c:34:11:b3:cb
D/MDMCTBK (  273): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 fc:94:e3:11:35:3a
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 fc:94:e3:11:35:3a
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 3679): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
I/wpa_supplicant( 3677): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3677): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
E/wpa_supplicant( 3679): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  387): NL - Read 312 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 192 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 68 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
I/wpa_supplicant( 3679): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  387): NL - Read 80 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 80 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/TCMD    (  387): NL - Read 68 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3679): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3679): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273):  STA Connected !!
D/TCMD    (  387): NL - Read 1000 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  273): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  273): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  273): get_freq !!, resp=0
I/MDMCTBK (  273): get_freq !!, Strip data
I/MDMCTBK (  273): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  273): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  273): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1202127648
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-32ms what=147462 obj=android.net.wifi.StateChangeResult@4280c9d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42772570 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42772570 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3561): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): my name is : motorola-XT1039_PT3477
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): attempting to connect to test coordinator
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): check test folder
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): found test : ./testFindPeers.js
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): found test : ./testReConnect.js
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): found test : ./testSendData.js
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): Test app app.js loaded
I/jxcore-log( 3561): 
,I/Choreographer( 3561): Skipped 226 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3561): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3561): 
,I/chromium( 3561): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 0
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 f
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 00
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 00
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 fc
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 fc
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@41f1b4a8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@41f1b4a8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@41f1b4a8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  387): NL - Read 60 bytes from update socket.
D/TCMD    (  387): NL - ignore NL message, type = 20
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): DHCP successful
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.123
,D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
,D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK,
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42010720
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1276): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/ModemStatsDSDetect( 1276): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42010720
I/ModemStatsDSDetect( 1276): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1276): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1276): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1276): onReceive() - done, currentInetCondition=0
,I/jxcore-log( 3561): DBG, CoordinatorConnector connect called
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): Coordinator is now connected to the server!
I/jxcore-log( 3561): 
,I/chromium( 3561): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,D/        ( 1019): Setting time of day to sec=1449007598
,W/        ( 1019): Unable to set rtc to 1449007598: Invalid argument
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1535): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3796 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1231): Column apn id key is 'apn_id'
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/PollingManager( 1535): now: 353978 ,futureTime: 46325731
,D/PollingManager( 1535): Polling alarm set to expire at: 46325731 Current Time: 353980
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler },
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,E/ActivityThread( 1535): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1535): registerApp(): CCE
I/CCE     ( 1535): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
D/TelephonyProvider( 1231): Column apn id key is 'apn_id'
D/CCE     ( 1535): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1535): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1535): now: 354017 ,futureTime: 46325731
,D/PollingManager( 1535): Polling alarm set to expire at: 46325731 Current Time: 354018
,E/ActivityThread( 1535): Failed to find provider info for com.motorola.blur.setupprovider
D/MMApiWebService( 1535): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1535): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1535): isRequestAllowed(): already have outstanding request ... ignoring request
D/CCE     ( 1535): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1535): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1535): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/OtaApp  ( 1535): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1535): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/OtaApp  ( 1535): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MMApiWebService( 1535): generating token using payload instead of using session token
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1535): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1535): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1535): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 1535): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1535): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1535): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1535): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/ActivityManager( 1019): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3835 uid=10056 gids={50056, 3003, 1028, 1015}
D/OtaApp  ( 1535): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/VacuumService( 1343): Vacuum at: now=1449007598318 tag=VacuumService
,D/dalvikvm( 3796): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f2a238, skipping init
I/openssl ( 3796): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3796): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3857 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3420:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TelephonyProvider( 1231): Column apn id key is 'apn_id'
,I/dalvikvm( 1381): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1381): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1381): VFY: replacing opcode 0x6e at 0x0033
,D/TelephonyProvider( 1231): Column apn id key is 'apn_id'
,V/MmsConfig( 3857): mnc/mcc: 
,V/MmsConfig( 3857): tag: bool value: enabledMMS - true
V/MmsConfig( 3857): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3857): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3857): tag: int value: maxImageWidth - 2592
D/GpsLocationProvider( 1019): NTP server returned: 1449007595154 (Tue Dec 01 23:06:35 CET 2015) reference: 350992 certainty: 15 system time offset: -3284
V/MmsConfig( 3857): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3857): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3857): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3857): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3857): tag: int value: recipientLimit - 20
I/dalvikvm( 1199): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1199): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1199): VFY: replacing opcode 0x6e at 0x0033
V/MmsConfig( 3857): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3857): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3857): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 3857): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3857): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3857): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3857): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3857): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3857): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,E/LocSvc_ApiV02( 1019): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/DelayedSyncController( 3835): Delaying sync.
,E/Auth.Api.Credentials( 1381): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3884 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3071:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1231): GC_EXPLICIT freed 1460K, 45% free 9517K/17224K, paused 2ms+4ms, total 34ms
I/ActivityManager( 1019): Killing 3443:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 3884): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3884): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3884): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3884): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3898 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3112:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1448988109047 min interval config: 0 actual interval: 19489523
,I/CheckinService( 1381): Checking schedule, now: 1449007598575 next: 1448988139016
,I/CheckinService( 1381): active receiver: enabled
,I/CheckinService( 1381): Preparing to send checkin request
,I/EventLogService( 1381): Accumulating logs since 1449006963515
,V/WebViewChromiumFactoryProvider( 3898): Binding Chromium to main looper Looper (main, tid 1) {41f26f88}
,I/LibraryLoader( 3898): Expected native library version number "",actual native library version number ""
,I/chromium( 3898): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3898): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3898): BLUETOOTH permission is missing!
,I/CheckinRequestBuilder( 1381): Checkin reason type: 8 attempt count: 1
,D/DelayedSyncController( 3835): Delaying sync.
,D/dalvikvm( 1381): GC_CONCURRENT freed 1679K, 32% free 11714K/17224K, paused 4ms+7ms, total 56ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 1805K, 65% free 17807K/50100K, paused 6ms+10ms, total 99ms
D/WifiService( 1019): New client listening to asynchronous messages
E/ActivityThread( 1381): Failed to find provider info for com.google.android.wearable.settings
,I/Adreno-EGL( 3898): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3898): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3898): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3898): Local Branch: 
I/Adreno-EGL( 3898): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3898): Local Patches: NONE
I/Adreno-EGL( 3898): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3898): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/jxcore-log( 3561): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3561): 
,W/GAV2    ( 3898): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3898): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3898): Starting up...
,I/ImageResourceManager( 3130): ImageResourceManager: uninitalized
,I/iu.Environment( 3130): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3130): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 3472:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3130): num queued entries: 0
,I/iu.UploadsManager( 3130): num updated entries: 0
,I/iu.SyncManager( 3130): NEXT; no task
,I/iu.SyncManager( 1381): SYNC; picasa accounts
,D/NetworkLogImpl( 1381): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1381): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1381): num queued entries: 0
,I/iu.UploadsManager( 1381): num updated entries: 0
,I/iu.SyncManager( 1381): NEXT; no task
,I/openssl ( 3796): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3796): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3884): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3884): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3130): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3956 uid=10007 gids={50007, 3003}
,D/MMApiWSBase( 1535): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1535): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1535): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/ExtensionsFactory( 3956): No custom extensions.
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3973 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 3155:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3984 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3645:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1019): Client connection lost with reason: 4
,D/Checkin ( 1535): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1535): handleGetNotificationsResponse(): got 0; more=false
,V/AlarmClock( 3973): AlarmInitReceiver android.intent.action.TIME_SET
,D/MMApiProvisionService( 1535): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"42302","deviceId":"1135300315450105856"}
D/MMApiProvisionService( 1535): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1535): doRequest(): /v1/dp/devices.json resp length: 137
,D/MMApiProvisionService( 1535): MMApiProvisionService.handleResponse (update_device) : true (None)
D/MMApiProvisionService( 1535): handleResponse(): Session Expiration alarm set to expire at: Wed Dec 02 10:51:41 CET 2015
,D/MMApiProvisionService( 1535): _setMMApiCredInfo: storing credential info 
,I/CalendarProvider2( 3984): Created com.android.providers.calendar.CalendarAlarmManager@41f42df8(com.android.providers.calendar.CalendarProvider2@41f3a9b0)
,E/MMApiProvisionService( 1535): handleResponse(): no settings sent by the server:
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1535): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,I/AlarmClock( 3973): Displaying next alarm time: ''
,V/AlarmClock( 3973): AlarmInitReceiver finished
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4001 uid=10098 gids={50098}
,D/dalvikvm( 4001): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41f2eec0, skipping init
D/TimeService( 4001): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449007599406
D/        ( 4001): TimeServiceNative: User Time to be set is 1449007599406
D/QC-time-services( 4001): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4001): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4001): Lib:time_genoff_operation: pargs->ts_val = 1449007599406
,D/QC-time-services(  336): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4001): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  336): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449007599406
D/QC-time-services(  336): Daemon:genoff_opr: Base = 2, val = 1449007599406, operation = 0
D/QC-time-services(  336): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/1/115 22:0:47
D/QC-time-services(  336): Daemon:Value read from RTC seconds = 1449007247000
D/QC-time-services(  336): Daemon:new time 1449007599406 
D/QC-time-services(  336): Daemon: delta 352406 genoff 352406 
D/QC-time-services(  336): Daemon:genoff_persistent_update: Writing genoff = 352406 to memory
D/QC-time-services(  336): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  336): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  336): Updating the TOD offset
D/QC-time-services(  336): Daemon:genoff_persistent_update: Writing genoff = 352406 to memory
D/QC-time-services(  336): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  336): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  336): Daemon:Update to modem bit set
D/QC-time-services(  336): Daemon:genoff_send_modem: Sending data to MODEM !
,E/QC-time-services( 4001): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  336): Daemon: Base = 2, Value being sent to MODEM = 18446743757745104022
,I/ActivityManager( 1019): Killing 3796:android.process.media/u0a18 (adj 15): empty #9
E/QC-time-services(  336): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  336): Daemon: Time-services: Waiting to acceptconnection
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1448988109047 min interval config: 0 actual interval: 19490388
,I/GCM     ( 1343): GCM config loaded
,D/UdcCache:FPQuery( 1381): Bootstrapping UDC settings cache for all accounts
,D/dalvikvm( 1343): GC_CONCURRENT freed 1921K, 39% free 10625K/17224K, paused 3ms+5ms, total 36ms
,I/GCM     ( 1343): Ack for not saved message 20
,D/DEBUG   ( 1535): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1535): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1535): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/DEBUG   ( 1535): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=1
,I/SundryService( 1535): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1535): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1535): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1535): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1535
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1535): GC_CONCURRENT freed 2929K, 38% free 10798K/17224K, paused 3ms+5ms, total 47ms
,D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4024 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,D/OtaApp  ( 1535): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1535): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1535
D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+4ms, total 21ms
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/IInputConnectionWrapper( 3561): showStatusIcon on inactive InputConnection
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,136
D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
W/dalvikvm( 4024): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 4024): VFY: replacing opcode 0x60 at 0x000b
I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
I/dalvikvm( 4024): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4024): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 4024): VFY: replacing opcode 0x6e at 0x00ca
D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/MultiDex( 4024): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4024): install
D/DEBUG   ( 1535): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/MultiDex( 4024): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SundryService( 1535): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1535): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1535): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{4206a6e8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
D/DEBUG   ( 1535): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
D/GetNotificationsWS( 1535): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1535): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1535): bindWebServices(): registering our AIDL callback...
I/SundryService( 1535): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1535): Received shoulder tap
D/GetNotificationsWS( 1535): onServiceConnected()
D/GetNotificationsWS( 1535): onServiceConnected(): Registered for remote service callbacks...
I/MultiDex( 4024): loading existing secondary dex files
I/MultiDex( 4024): load found 3 secondary dex files
,I/MultiDex( 4024): install done
,D/dalvikvm( 4024): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4024): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4024): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4024): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4024): VFY: unable to resolve instance field 46
,D/dalvikvm( 4024): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4024): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,D/WaitableIntentService( 1535): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
W/dalvikvm( 4024): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4024): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4024): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4024): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 4024): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f308a8
,D/GetNotificationsWS( 1535): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/dalvikvm( 4024): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f308a8
,D/dalvikvm( 4024): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f308a8, skipping init
D/GetNotificationsWS( 1535): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/dalvikvm( 4024): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f308a8
D/dalvikvm( 4024): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f308a8
,V/JNIHelp ( 4024): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/MMApiWSBase( 1535): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/GetConfigurationSnapshotOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm( 4024): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f308a8
,D/dalvikvm( 4024): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41f308a8
D/dalvikvm( 4024): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f308a8
,D/dalvikvm( 4024): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f308a8
,I/PhenotypeFlagCommitter( 1343): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1343): Using platform SSLCertificateSocketFactory
,I/ProviderInstaller( 4024): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1199): callingUid 10022, callindPid: 1199
,E/MDM     ( 1199): [75] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/dalvikvm( 4024): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 4024): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4024): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1381): Restart initialization of location
,D/AuthorizationBluetoothService( 1343): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1343): Proximity feature is not enabled.
,I/dalvikvm( 4024): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 4024): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4024): VFY: replacing opcode 0x6e at 0x0220
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4024): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4024): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 4024): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 4024): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 4024): VFY: replacing opcode 0x22 at 0x0000
,I/dalvikvm( 4024): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 4024): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4024): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4024): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 4024): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/dalvikvm( 4024): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1276): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1276): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1276): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1276): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/GCoreFlp( 1199): No location to return for getLastLocation()
,W/FusedLocationProvider( 1343): location=null
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,V/GmsCoreStatsServiceLauncher( 1381): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  279): App is not loaded in QSEE
,I/dalvikvm( 4024): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 4024): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4024): VFY: replacing opcode 0x6e at 0x0033
,W/dalvikvm( 4024): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4024): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4024): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4024): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4024): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4024): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 4024): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  279): Loaded image: APP id = 3
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53d1000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53d1000
,D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=2420975239
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4024): Install completed successfully. count=13 extracted=0
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
D/MMApiWSBase( 1535): doRequest(): v1/ns/list/messages resp length: 1465
D/CCE     ( 1535): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
D/CCE     ( 1535): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/dalvikvm( 1535): Jit: resizing JitTable from 4096 to 8192
,I/CalendarProvider2( 3984): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3984): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Checkin ( 1535): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1535): handleGetNotificationsResponse(): got 0; more=false
,D/AlertReceiver( 3956): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/dalvikvm( 1343): GC_CONCURRENT freed 1682K, 37% free 10962K/17224K, paused 3ms+6ms, total 48ms
,D/AlertService( 3956): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/DEBUG   ( 1535): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1535): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1535): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1535): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1535): unbindWebServices(): un-registering our AIDL callback...
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,W/Uploader( 1343):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1343): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 4024): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422d1180
,D/dalvikvm( 4024): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422d1180
,D/dalvikvm( 4024): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422d1180, skipping init
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=2789623298
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4024): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4071): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4024): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4024): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 69ms
,I/Adreno-EGL( 4024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4024): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4024): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4024): Local Branch: 
I/Adreno-EGL( 4024): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4024): Local Patches: NONE
I/Adreno-EGL( 4024): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4024): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4024): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4024): Local Branch: 
I/Adreno-EGL( 4024): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4024): Local Patches: NONE
I/Adreno-EGL( 4024): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4024): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4024): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4024): Local Branch: 
I/Adreno-EGL( 4024): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4024): Local Patches: NONE
I/Adreno-EGL( 4024): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4024): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4024): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4024): Local Branch: 
I/Adreno-EGL( 4024): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4024): Local Patches: NONE
I/Adreno-EGL( 4024): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4024): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1381): Classify the device as Phone.
,I/CheckinTask( 1381): Sending checkin request (12406 bytes)
,I/CheckinResponseProcessor( 1381): From server: 1 gservices updates and 0 deletes
,D/dalvikvm( 1019): GC_EXPLICIT freed 814K, 65% free 17816K/50100K, paused 4ms+10ms, total 99ms
,E/UlpEngine( 1019): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,E/UlpEngine( 1019): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,I/CertBlacklister( 1019): Certificate blacklist changed, updating...
,I/CertBlacklister( 1019): Certificate blacklist updated
,I/GservicesProvider( 1343): main difference update completed
,I/ActivityManager( 1019): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4086 uid=10009 gids={50009, 3003, 2001}
,I/CheckinRequestBuilder( 1381): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1381): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4086): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4086): Update started
,E/UpdateRequestReceiver( 4086): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4110 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,W/ContextImpl( 4086): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4086): Update started
,E/UpdateRequestReceiver( 4086): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4086): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/dalvikvm( 1343): null clazz in OP_INSTANCE_OF, single-stepping
,E/UpdateRequestReceiver( 4086): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager( 1019): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4131 uid=10025 gids={50025, 3003}
,I/CheckinRequestBuilder( 1381): Classify the device as Phone.
,D/dalvikvm( 4110): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f29498, skipping init
I/openssl ( 4110): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4110): Crypto mode 0 already enabled
,I/CheckinTask( 1381): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1381): Checking schedule, now: 1449007603533 next: 1449600673525
,I/CheckinService( 1381): active receiver: disabled
,I/ContactAccountLoggerTas( 2210): canRun() : Opted Out
,I/Search.GservicesUpdateTask( 2210): Updating Gservices keys
,D/CheckinService( 1381): Recording last checkin time for package unspecified as 1449007603572
,I/ContactAccountLoggerTas( 2210): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2210): canRun() : Opted Out
,I/DownloadManager( 4110): Download 235 starting
,W/ActivityThread( 4110): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ContactAccountLoggerTas( 2210): canRun() : Opted Out
,I/ActivityManager( 1019): Killing 3857:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/DownloadManager( 4110): Download 236 starting
,I/ActivityManager( 1019): Killing 3835:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 1381): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1381): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1381): VFY: replacing opcode 0x71 at 0x0046
,D/dalvikvm( 3130): GC_FOR_ALLOC freed 747K, 15% free 14793K/17224K, paused 17ms, total 18ms
,I/dalvikvm-heap( 3130): Grow heap (frag case) to 18.215MB for 1821008-byte allocation
,D/dalvikvm( 1381): GC_CONCURRENT freed 2090K, 33% free 11666K/17224K, paused 5ms+4ms, total 58ms
,D/dalvikvm( 1381): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 3130): GC_FOR_ALLOC freed 43K, 14% free 16533K/19004K, paused 12ms, total 12ms
,I/dalvikvm-heap( 3130): Grow heap (frag case) to 19.915MB for 1821008-byte allocation
,D/dalvikvm( 1343): GC_EXPLICIT freed 1429K, 37% free 10963K/17224K, paused 3ms+6ms, total 36ms
,I/GAV2    ( 3898): Thread[GAThread,5,main]: No campaign data found.
,I/DownloadManager( 4110): Ignoring Content-Length since Transfer-Encoding is also defined
,D/Checkin ( 4110): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4110): Download 235 finished with status SUCCESS
,D/dalvikvm( 1343): GC_EXPLICIT freed 558K, 38% free 10801K/17224K, paused 3ms+5ms, total 33ms
,I/DownloadManager( 4110): Ignoring Content-Length since Transfer-Encoding is also defined
,D/SystemEventReceiver( 1381): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1381): Updating ocr activity enabled=false
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1449007603572 min interval config: 0 actual interval: 706
,I/Auth    ( 1343): [BroadcastManager] Broadcasting account services changed.
,D/Checkin ( 4110): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4110): Download 236 finished with status SUCCESS
,I/ActivityManager( 1019): Killing 3898:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1381): GC_EXPLICIT freed 475K, 32% free 11743K/17224K, paused 4ms+16ms, total 57ms
,W/SQLiteConnectionPool( 1381): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/CheckinService( 1381): Checking schedule, now: 1449007604364 next: 1449600673525
,I/CheckinService( 1381): active receiver: disabled
,D/dalvikvm( 1019): GC_EXPLICIT freed 768K, 65% free 17688K/50100K, paused 4ms+9ms, total 87ms
,I/SystemUpdateService( 1381): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,D/SystemUpdateService( 1381): onCreate
,D/SystemUpdateService( 1381): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/OcrModelManager( 1381): Updating downloaded model state (gservices changed)
,I/SystemUpdateService( 1381): cancelUpdate (empty URL)
,I/SystemUpdateService( 1381): active receiver: disabled
,D/SystemUpdateService( 1381): onDestroy
,D/GCM     ( 1343): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1199): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1199): DispatchingService.onCreate()
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1199): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ContextImpl( 4086): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/openssl ( 4110): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4110): Crypto mode 0 already enabled
,W/ContextImpl( 4086): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/GCoreUlr( 1199): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1199): Unbound from all location providers
,I/GCoreUlr( 1199): DispatchingService.onDestroy()
,I/GCoreUlr( 1199): Stopping handler for UlrDispSvcFast
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1199): Unbound from all location providers
,I/DownloadManager( 4110): Download 237 starting
,I/DownloadManager( 4110): Download 238 starting
,I/DownloadManager( 4110): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 4110): Ignoring Content-Length since Transfer-Encoding is also defined
,I/Auth    ( 1343): [BroadcastManager] Broadcasting account services changed.
,D/Checkin ( 4110): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4110): Download 237 finished with status SUCCESS
,D/Checkin ( 4110): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,W/ContextImpl( 4086): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4086): Update downloaded, starting installation
,I/UpdateFetcherService( 4086): Started installation
,I/DownloadManager( 4110): Download 238 finished with status SUCCESS
,W/ContextImpl( 4086): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4086): Update downloaded, starting installation
,I/UpdateFetcherService( 4086): Started installation
,I/ConfigUpdateInstallReceiver( 1019): Not installing, new version is <= current version
,I/GlobalDismissManager( 3956): no sender configured
,D/AlertService( 3956): Beginning updateAlertNotification
,D/AlertService( 3956): No fired or scheduled alerts
,D/AlertService( 3956): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3956): No events found starting within 1 week.
I/ActivityManager( 1019): Killing 3984:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactAccountLoggerTas( 2210): canRun() : Opted Out
,I/ActivityManager( 1019): Killing 4001:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4243 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/dalvikvm( 3130): GC_FOR_ALLOC freed 13K, 12% free 18322K/20784K, paused 93ms, total 93ms
,I/Launcher( 1292): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/Launcher( 1292): Deferring update until onResume
I/dalvikvm-heap( 3130): Grow heap (frag case) to 21.663MB for 1821008-byte allocation
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/GAV2    ( 3130): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1199): DISABLE
,I/GCoreNlp( 1199): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4243): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4243): MmsConfig.loadMmsSettings
I/Babel   ( 4243): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4243): MmsConfig.loadFromDatabase
,E/Babel   ( 4243): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4243): MmsConfig.loadFromResources
,E/Babel   ( 4243): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4243): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4243): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4280 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm( 1019): GC_CONCURRENT freed 1805K, 65% free 17941K/50100K, paused 4ms+9ms, total 82ms
,D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 158K, 65% free 17783K/50100K, paused 3ms+9ms, total 88ms
I/ActivityManager( 1019): Killing 3973:com.android.deskclock/u0a15 (adj 15): empty #9
I/ActivityManager( 1019): Killing 3956:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4299 uid=10033 gids={50033, 3003, 1028, 1015}
I/ContactLocale( 4280): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/InternalIcingCorporaPro( 2210): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1381): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4318 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4131:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageBroadcastService( 1381): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1381): updateResources: need to parse f{com.google.android.gms}
,I/dalvikvm( 4318): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4318): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4318): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4318): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4318): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4318): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 4318): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x000a
,I/InternalIcingCorporaPro( 2210): UpdateCorporaTask done [took 235 ms] updated apps [took 234 ms] 
,D/Finsky  ( 4318): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4318): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4318): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4318): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4318): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4318): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4318): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4318): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4318): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4318): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4318): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4318): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4318): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4318): Skipping gmscore version check
,D/Finsky  ( 4318): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4318): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4318): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4318): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4318): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x0017
,D/Finsky  ( 4318): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1019): Killing 3884:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/PackageSettings( 1019): Skipping PackageSetting{421e75a0 com.example.hello/10416} due to missing metadata
,V/AlarmManager( 1019): sending alarm Alarm{445fd360 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4278a268 type 2 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4274b3e8 type 3 android}
,I/jxcore-log( 3561): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): DBG, CoordinatorConnector command called
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"58:2A:F7:ED:96
,I/jxcore-log( 3561): Start now : testSendData.js
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): check server
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): serverPort is 34248
I/jxcore-log( 3561): 
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/        ( 3561): Stoping All
I/        ( 3561): Stopping services
,I/        ( 3561): Stop Bluetooth
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3561): Start-My BT: F4:F1:E1:5C:3B:E2
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3561):  mInstanceString : {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}
,I/        ( 3561): All stuff available and enabled
,I/        ( 3561): Stoping All
I/        ( 3561): Stopping services
I/        ( 3561): Stop Bluetooth
I/        ( 3561): Starting All
I/        ( 3561): Stopping services
,I/        ( 3561): Starting services address: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@41fb9c50
I/        ( 3561): Stopping services
,I/        ( 3561): Starting services address: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}
,I/        ( 3561): Add local service :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3477"}, length : 81
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9ebd158 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9ebd158 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState add service
,D/WifiP2pService( 1019): add a new client
,I/        ( 3561): peerDiscoveryTimer timeout value:9924
D/WifiP2pService( 1019): InactiveState{ when=0 what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/WifiP2pService( 1019): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): discovery change broadcast true
I/        ( 3561): Stop Bluetooth
I/        ( 3561): StartBluetooth listener
I/        ( 3561): StartBluetooth listener
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3607): SOCK FLAG = 0 ***********************
I/jxcore-log( 3561): StartBroadcasting started ok
I/jxcore-log( 3561): 
I/jxcore-log( 3561): do fake peer & start
I/jxcore-log( 3561): 
I/jxcore-log( 3561): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:08:17.156Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:08:17.157Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:08:17.157Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
I/BTListenerThread( 3561): starting to listen
I/BTListenerThread( 3561): waiting to accept incoming Connection
I/        ( 3561): Selected device address: 00:F4:6F:30:E0:6C, name: null
I/        ( 3561): Connecting to null, at 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 2015-12-01T22:08:17.163Z SendDataTCPServer.js: TCP/IP server is bound to port: 34248
I/jxcore-log( 3561): 
I/chromium( 3561): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/WB      ( 3561): We already were running, thus doing nothing
I/        ( 3561): Added local service
I/        ( 3561): Cleared service requests
I/        ( 3561): Stopped peer discovery
I/        ( 3561): Started peer discovery
I/        ( 3561): Discovery state changed to Started.
I/BTConnectToThread( 3561): Starting to connect
W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[128]}
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 1 peers.
,I/SS      ( 3561): Peer(1): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/        ( 3561): Started service discovery
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-rfcomm( 3607): PORT_StartCnf failed result:5
,W/bt-btif ( 3607): invalid rfc slot id: 6
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BluetoothBondStateMachine( 3607): No record of the device:null
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 9 Address: 00:F4:6F:30:E0:6C newState: 0
,E/BluetoothBondStateMachine( 3607): In stable state, received invalid newState: 10
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:08:21.246Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:08:21.246Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:21.247Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=1
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3607): bta_dm_check_av:0
,E/bt-btif ( 3607): Do not find the bg connection mask for the remote device
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3607): Entering PendingCommandState State
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4218a080:true
I/ActivityManager( 1019): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=4391 uid=10011 gids={50011, 3003, 3002, 3001}
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420e6c70:true
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=4409 uid=10016 gids={50016, 3002}
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,I/ActivityManager( 1019): Killing 4086:com.google.android.configupdater/u0a9 (adj 15): empty #9
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3607): Ftp Service onStartCommand
V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3607): services_to_search = 3fffffff
,E/bt-btif ( 3607): ****************search UUID = 1200***********
,I/ActivityManager( 1019): Killing 4024:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218528 rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): services_to_search = 3ffffffe
,E/bt-btif ( 3607): ****************search UUID = 0100***********
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:255
W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3561): we got incoming connection
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3561): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/BTListenerThread( 3561): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3561): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3561): MESSAGE_WRITE 81 bytes.
,I/HS      ( 3561): Incoming connection Hand Shake finished for : motorola-XT1072_PT7532
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : true, motorola-XT1072_PT7532
,I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BTConnectedThread
,I/BtConnectorHelper( 3561): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3561): --DoOneRunRound started
,I/jxcore-log( 3561): 2015-12-01T22:08:23.379Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): LocalHost address: localhost/127.0.0.1, port: 34248
,I/BtToRequestSocket( 3561): --DoOneRunRound ended
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 3 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 8 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
D/BluetoothAdapterProperties( 3607): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3607): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,D/BluetoothMetrics( 3607): btclass5a020c
,D/Checkin ( 3607): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3561): 2015-12-01T22:08:24.391Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:24.403Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:24.628Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:24.935Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:24.938Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:24.946Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.005Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.044Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.056Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.110Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.120Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.154Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.269Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.281Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.303Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3561): 
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-42
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-13ms what=147477 obj=Device: Android_8ae2,
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-15ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 3561): 2015-12-01T22:08:25.468Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.503Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.511Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.535Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.555Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.631Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.645Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.654Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.668Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.756Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.795Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.834Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.856Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.875Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.915Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.955Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:25.960Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.020Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.055Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.060Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.094Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.236Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.248Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.250Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.334Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:08:26.443Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.473Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:26.514Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3561): 
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2,
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-37
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2,
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService( 1019):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService( 1019):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 92
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9552","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9552, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9552, WifiDirectName: Android_608e, WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 82
,I/jxcore-log( 3561): 2015-12-01T22:08:31.258Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:31.259Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:31.261Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:31.264Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3561): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[132]}
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-38
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-10ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-11ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218528 rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): invalid rfc slot id: 5
,I/BtToSocketBase( 3561): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Close LocalOutputStream
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt socket
,I/BtToSocketBase( 3561): Close bt socket
,I/jxcore-log( 3561): 2015-12-01T22:08:36.645Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-rfcomm( 3607): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3607): RFCOMM_DisconnectInd LCID:0x44
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,I/ClearcutLoggerApiImpl( 1343): disconnect managed GoogleApiClient
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-34
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 8 peers.
I/SS      ( 3561): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(3): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3561): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(7): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3561): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=11 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218528 rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3607): L2CAP - con rsp - bad ID. Exp: 5 Got: 4
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-11
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-48
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-6ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3607): Entering PendingCommandState State
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3607): services_to_search = 3fffffff
,E/bt-btif ( 3607): ****************search UUID = 1200***********
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): services_to_search = 3ffffffe
,E/bt-btif ( 3607): ****************search UUID = 0100***********
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:1
W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3561): Starting to Handshake
I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3561): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/BTConnectToThread( 3561): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3561): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3561): HandshakeOk : samsung-SM-G800F_PT8573
,I/HS      ( 3561): Hand Shake finished outgoing for : samsung-SM-G800F_PT8573
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : false, samsung-SM-G800F_PT8573
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3561): mHTTPPort  set to : 41750
I/BtConnectorHelper( 3561): Request socket is using : 41750
,I/BtToRequestSocket( 3561): Now accepting connections
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,I/BtConnectorHelper( 3561): Calling ConnectionStatusUpdate with port :41750
,I/jxcore-log( 3561): 2015-12-01T22:08:42.904Z SendDataConnector.js: CLIENT connected to 41750, error: null
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:42.906Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): incoming data from: /127.0.0.1, port: 41750
,I/BtToRequestSocket( 3561): Set local streams
,I/BtToRequestSocket( 3561): rin ended ---------------------------;
,I/jxcore-log( 3561): 2015-12-01T22:08:42.935Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3561): 
,E/bt-btif ( 3607): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
D/BluetoothAdapterProperties( 3607): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3607): Failed to remove device: 00:F4:6F:30:E0:6C
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,D/BluetoothMetrics( 3607): btclass1f00
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/Checkin ( 3607): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 82
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:08:44.152Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:44.465Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:44.620Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:44.878Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:08:45.141Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:45.330Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3561): 
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3561): 2015-12-01T22:08:46.123Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:46.258Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:08:46.383Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3561): 
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3561): we got incoming connection
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
I/BTListenerThread( 3561): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/BTListenerThread( 3561): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3561): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3561): MESSAGE_WRITE 81 bytes.
,I/HS      ( 3561): Incoming connection Hand Shake finished for : motorola-XT1072_PT7532
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : true, motorola-XT1072_PT7532
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3561): Creating BTConnectedThread
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3561): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3561): --DoOneRunRound started
,I/BtToRequestSocket( 3561): LocalHost address: localhost/127.0.0.1, port: 34248
,I/jxcore-log( 3561): 2015-12-01T22:08:47.457Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): --DoOneRunRound ended
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:08:47.904Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:47.935Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:47.957Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:47.964Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:47.967Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:47.974Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3561): 
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-34
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-9ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-11ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218528 rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-39
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -39 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 1
,W/bt-btif ( 3607): proc dm_pm_timer expires
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 3561): 2015-12-01T22:08:56.385Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:56.386Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:56.389Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:56.391Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:08:56.402Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3561): 
,I/BtToSocketBase( 3561): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3561): Disconnect outgoing peer: samsung-SM-G800F_PT8573
,I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Close LocalOutputStream
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt socket
,I/BtToRequestSocket( 3561): Close server socket
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 3607): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): invalid rfc slot id: 7
,I/BtToSocketBase( 3561): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
,I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
,I/BtToSocketBase( 3561): Close LocalOutputStream
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt in
I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt socket
,I/BtToSocketBase( 3561): Close bt socket
,I/jxcore-log( 3561): 2015-12-01T22:08:58.005Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3561): 
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218528 rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3607): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3607): RFCOMM_DisconnectInd LCID:0x4d
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 b6
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 b6
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 82
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,V/AlarmManager( 1019): sending alarm Alarm{428370a8 type 3 android}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/WifiP2pService( 1019): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:09:01.401Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:01.403Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end,
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-31
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 3561): 2015-12-01T22:09:06.408Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:06.409Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:06.410Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:06.413Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3561): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[130]}
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3561): Starting to Handshake
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3561): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/BTConnectToThread( 3561): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3561): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3561): HandshakeOk : samsung-SM-G800F_PT8573
I/HS      ( 3561): Hand Shake finished outgoing for : samsung-SM-G800F_PT8573
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : false, samsung-SM-G800F_PT8573
,I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): mHTTPPort  set to : 49989
,I/BtConnectorHelper( 3561): Request socket is using : 49989
,I/BtToRequestSocket( 3561): Now accepting connections
,I/BtConnectorHelper( 3561): Calling ConnectionStatusUpdate with port :49989
,I/jxcore-log( 3561): 2015-12-01T22:09:09.138Z SendDataConnector.js: CLIENT connected to 49989, error: null
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:09.140Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): incoming data from: /127.0.0.1, port: 49989
,I/BtToRequestSocket( 3561): Set local streams
,I/jxcore-log( 3561): 2015-12-01T22:09:09.158Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): rin ended ---------------------------;
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218528 rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-47
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:09:19.235Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:19.236Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:19.240Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:19.241Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:19.243Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3561): 
,I/BtToSocketBase( 3561): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3561): Disconnect outgoing peer: samsung-SM-G800F_PT8573
I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
I/BtToSocketBase( 3561): Close local in
I/BtToSocketBase( 3561): Close LocalOutputStream
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt socket
,I/BtToRequestSocket( 3561): Close server socket
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 b6
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 b6
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
,D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-12ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 10 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(7): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(9): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3561): Peer(10): Android_63cc 82:01:84:6b:e8:5d
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService( 1019): InactiveState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/jxcore-log( 3561): 2015-12-01T22:09:24.244Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:24.245Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-47
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-31
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2,
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-46
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2,
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6355","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6355, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6355, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 fa
,I/jxcore-log( 3561): 2015-12-01T22:09:29.250Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:29.251Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:29.253Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:29.255Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3561): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[131]}
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-31
,D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2,
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/WifiP2pService( 1019): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3561): Starting to Handshake
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3561): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3561): we got incoming connection
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3561): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-44
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,I/BTConnectToThread( 3561): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3561): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3561): HandshakeOk : samsung-SM-G800F_PT8573
I/HS      ( 3561): Hand Shake finished outgoing for : samsung-SM-G800F_PT8573
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : false, samsung-SM-G800F_PT8573
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): mHTTPPort  set to : 53385
,I/BtConnectorHelper( 3561): Request socket is using : 53385
,I/BtToRequestSocket( 3561): Now accepting connections
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218528 rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/BTListenerThread( 3561): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3561): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT7532","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3561): MESSAGE_WRITE 81 bytes.
I/HS      ( 3561): Incoming connection Hand Shake finished for : motorola-XT1072_PT7532
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3561): Starting the connected thread incoming : true, motorola-XT1072_PT7532
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BTConnectedThread
,I/BtConnectorHelper( 3561): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3561): --DoOneRunRound started
,I/BtToRequestSocket( 3561): LocalHost address: localhost/127.0.0.1, port: 34248
,I/BtToRequestSocket( 3561): --DoOneRunRound ended
,I/jxcore-log( 3561): 2015-12-01T22:09:32.754Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3561): 
,I/BtConnectorHelper( 3561): Calling ConnectionStatusUpdate with port :53385
,I/jxcore-log( 3561): 2015-12-01T22:09:32.775Z SendDataConnector.js: CLIENT connected to 53385, error: null
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:32.775Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): incoming data from: /127.0.0.1, port: 53385
I/BtToRequestSocket( 3561): Set local streams
,I/BtToRequestSocket( 3561): rin ended ---------------------------;
,I/jxcore-log( 3561): 2015-12-01T22:09:32.780Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:33.215Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:33.225Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:33.232Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:33.237Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:33.245Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:33.266Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 1
,W/bt-btif ( 3607): proc dm_pm_timer expires
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 b6
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 b6
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 c0
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 c0
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,I/jxcore-log( 3561): 2015-12-01T22:09:42.846Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:42.846Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:42.849Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:42.850Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:42.853Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3561): 
,I/BtToSocketBase( 3561): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3561): Disconnect outgoing peer: samsung-SM-G800F_PT8573
,I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Close LocalOutputStream,
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt socket
,I/BtToRequestSocket( 3561): Close server socket
,W/bt-btif ( 3607): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,W/bt-btif ( 3607): invalid rfc slot id: 9
,I/BtToSocketBase( 3561): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
,I/BtToSocketBase( 3561): Stop ReceivingThread
,I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT7532
,I/BtToSocketBase( 3561): Close LocalOutputStream
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt socket
,I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt socket
,I/jxcore-log( 3561): 2015-12-01T22:09:43.206Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3561): 
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3607): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 3607): RFCOMM_DisconnectInd LCID:0x46
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-38
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 13 peers.
I/SS      ( 3561): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3561): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(8): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(9): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3561): Peer(10): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(11): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3561): Peer(12): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3561): Peer(13): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=21 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218528 rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 fa
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-FIND-STOPPED 
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  273): Event received = P2P-FIND-STOPPED 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
D/WifiP2pService( 1019): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): discovery change broadcast false
D/WifiP2pService( 1019): InactiveState{ when=0 what=139265 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139265 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 3561): Discovery state changed to Stopped.
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): discovery change broadcast true
I/        ( 3561): Started peer discovery
I/        ( 3561): Discovery state changed to Started.
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-31
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2,
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-37
,D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2,
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-38
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2,
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2,
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag,
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
D/WifiP2pService( 1019): P2pEnabledState{ when=-16ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
D/WifiP2pService( 1019): InactiveState{ when=-16ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-16ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-17ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-19ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-7ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-9ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-14ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-14ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 14 peers.
,D/WifiP2pService( 1019): DefaultState{ when=-14ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3561): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3561): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3561): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3561): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(10): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(11): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(12): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(13): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(14): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1019): InactiveState{ when=-13ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-14ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-15ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-14ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-14ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-14ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-11ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-11ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-11ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-6ms what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3607): Ftp Service onStartCommand
D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState add service request
V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
D/WifiP2pManager( 3561): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
I/        ( 3561): Added service request
V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/jxcore-log( 3561): 2015-12-01T22:09:47.853Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:47.854Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-30
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService( 1019): InactiveState{ when=-14ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-15ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 10 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 82
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:09:52.857Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:52.858Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:52.860Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:52.861Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 00:F4:6F:30:E0:6C, name: S5mini-1
,I/        ( 3561): Connecting to S5mini-1, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[135]}
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 44
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 44
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3561): Starting to Handshake
I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3561): MESSAGE_WRITE 81 bytes.
I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/BTConnectToThread( 3561): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3561): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3561): HandshakeOk : samsung-SM-G800F_PT8573
,I/HS      ( 3561): Hand Shake finished outgoing for : samsung-SM-G800F_PT8573
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : false, samsung-SM-G800F_PT8573
,I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): mHTTPPort  set to : 59203
,I/BtConnectorHelper( 3561): Request socket is using : 59203
,I/BtToRequestSocket( 3561): Now accepting connections
,I/BtConnectorHelper( 3561): Calling ConnectionStatusUpdate with port :59203
,I/jxcore-log( 3561): 2015-12-01T22:09:56.020Z SendDataConnector.js: CLIENT connected to 59203, error: null
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:09:56.022Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): incoming data from: /127.0.0.1, port: 59203
,I/BtToRequestSocket( 3561): Set local streams
,I/jxcore-log( 3561): 2015-12-01T22:09:56.037Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): rin ended ---------------------------;
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 fa
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/dalvikvm( 1019): GC_CONCURRENT freed 1734K, 64% free 18124K/50068K, paused 7ms+9ms, total 93ms
,V/AlarmManager( 1019): sending alarm Alarm{445b9388 type 3 android}
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 11 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 11 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2,
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29,
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2,
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 14 peers.
I/SS      ( 3561): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3561): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(5): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3561): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3561): Peer(8): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3561): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(10): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(11): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(12): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(13): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3561): Peer(14): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3607): Entering PendingCommandState State
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 10
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 10
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,E/bt-btif ( 3607): services_to_search = 3fffffff
,E/bt-btif ( 3607): ****************search UUID = 1200***********
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): services_to_search = 3ffffffe
,E/bt-btif ( 3607): ****************search UUID = 0100***********
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3561): we got incoming connection
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3561): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/BTListenerThread( 3561): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3561): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8176","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3561): MESSAGE_WRITE 81 bytes.
,I/HS      ( 3561): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT8176
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : true, LGE-Nexus 5_PT8176
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BTConnectedThread
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3561): --DoOneRunRound started
,I/BtToRequestSocket( 3561): LocalHost address: localhost/127.0.0.1, port: 34248
,I/jxcore-log( 3561): 2015-12-01T22:10:01.245Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): --DoOneRunRound ended
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3607): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3607): Failed to remove device: 34:FC:EF:11:AE:67
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,D/BluetoothMetrics( 3607): btclass5a020c
,D/Checkin ( 3607): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 12 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 12 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2,
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2,
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 3561): 2015-12-01T22:10:02.059Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.069Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.078Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.083Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.099Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.108Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.117Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.154Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.166Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.184Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.195Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.199Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.210Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.246Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.251Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.340Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.376Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.397Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.434Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.454Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.466Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.504Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.509Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.514Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.526Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.529Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.566Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.575Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.615Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.656Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.694Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.734Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.767Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:02.804Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3561): 
,W/bt-btif ( 3607): invalid rfc slot id: 12
,I/BtToSocketBase( 3561): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8176
,I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8176
,I/BtToSocketBase( 3561): Close LocalOutputStream
,I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt socket
,I/BtToSocketBase( 3561): Close bt socket
,I/jxcore-log( 3561): 2015-12-01T22:10:02.846Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3561): 
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-rfcomm( 3607): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 3607): RFCOMM_DisconnectInd LCID:0x4c
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-38
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/jxcore-log( 3561): 2015-12-01T22:10:06.120Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:06.120Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:06.123Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:06.149Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:06.150Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:06.150Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
I/BtConnectorHelper( 3561): Disconnect outgoing peer: 00:F4:6F:30:E0:6C
I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3561): Close LocalOutputStream
,I/BtToSocketBase( 3561): Close localHostSocket
I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt socket
,I/BtToRequestSocket( 3561): Close server socket
,I/jxcore-log( 3561): 2015-12-01T22:10:06.156Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): ---- round done--------
I/jxcore-log( 3561): 
I/jxcore-log( 3561): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3561): 
I/jxcore-log( 3561): do fake peer & start
I/jxcore-log( 3561): 
I/jxcore-log( 3561): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:06.158Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:10:06.159Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:06.159Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3561): Connecting to null, at F8:95:C7:87:3C:51
,I/jxcore-log( 3561): 2015-12-01T22:10:06.164Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3561): 
,I/chromium( 3561): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[136]}
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f2186e4 rs_disc_pending=1
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f2188a0 rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3607): Entering PendingCommandState State
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3607): services_to_search = 3fffffff
,E/bt-btif ( 3607): ****************search UUID = 1200***********
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): services_to_search = 3ffffffe
,E/bt-btif ( 3607): ****************search UUID = 0100***********
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3561): Starting to Handshake
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3561): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/BTConnectToThread( 3561): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3561): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3561): HandshakeOk : LGE-LG-H815_PT5589
I/HS      ( 3561): Hand Shake finished outgoing for : LGE-LG-H815_PT5589
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : false, LGE-LG-H815_PT5589
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): mHTTPPort  set to : 55618
,I/BtConnectorHelper( 3561): Request socket is using : 55618
,I/BtToRequestSocket( 3561): Now accepting connections
,I/BtConnectorHelper( 3561): Calling ConnectionStatusUpdate with port :55618
,I/jxcore-log( 3561): 2015-12-01T22:10:08.045Z SendDataConnector.js: CLIENT connected to 55618, error: null
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:08.046Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): incoming data from: /127.0.0.1, port: 55618
,I/BtToRequestSocket( 3561): Set local streams
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3561): 2015-12-01T22:10:08.062Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): rin ended ---------------------------;
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 3 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3607): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3607): Failed to remove device: F8:95:C7:87:3C:51
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,D/BluetoothMetrics( 3607): btclass1f00
,D/Checkin ( 3607): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 fa
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:10:08.903Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3561): 
,W/bt-btif ( 3607): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3561): 2015-12-01T22:10:09.010Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:09.193Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:09.267Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:09.367Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:09.480Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:09.570Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:09.760Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:09.805Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3561): 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 12
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 12
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 a2
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 a2
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27,
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b
D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-18ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-19ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139307 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 13 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 13 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/jxcore-log( 3561): 2015-12-01T22:10:19.805Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:19.806Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:19.808Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:19.810Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:19.812Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3561): 
,I/BtToSocketBase( 3561): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3561): Disconnect outgoing peer: LGE-LG-H815_PT5589
,I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Close LocalOutputStream
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt socket
,I/BtToRequestSocket( 3561): Close server socket
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 13
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 13
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-23
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 14 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 14 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-34
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2,
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 3561): Found 12 peers.
,I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3561): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(9): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3561): Peer(10): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(11): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3561): Peer(12): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139301 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-38
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiP2pService( 1019): InactiveState{ when=-28ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-28ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 3561): Started service discovery
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 3561): 2015-12-01T22:10:24.813Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:24.814Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 82
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/dalvikvm( 1019): GC_EXPLICIT freed 600K, 65% free 17968K/50068K, paused 6ms+8ms, total 112ms
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-30
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-35
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2,
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-38
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2,
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -35 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,E/bt-btm  ( 3607): RS in progress - Set DISC Pending flag in btm_sec_send_hci_disconnect to delay disconnect
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ee
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 ee
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-30
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3561): 2015-12-01T22:10:29.817Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:29.818Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:29.820Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:29.821Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3561): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[137]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 44
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 44
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 14
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 14
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 fa
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 15 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 15 c
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
,D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 92
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=139307 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 3561): Cleared service requests
I/        ( 3561): Started peer discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2,
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 12 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(9): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(10): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(11): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3561): Peer(12): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=48 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139301 arg2=48 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 15
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 15
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 3a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 3a
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 16 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 16 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2,
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ee
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 ee
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-30
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-30
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2,
,D/WifiP2pService( 1019): InactiveState{ when=-9ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-btm  ( 3607): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f21836c rs_disc_pending=2
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-39
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -39 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218a5c rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218a5c rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3607): Entering PendingCommandState State
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
,E/bt-btif ( 3607): services_to_search = 3fffffff
,E/bt-btif ( 3607): ****************search UUID = 1200***********
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): services_to_search = 3ffffffe
,E/bt-btif ( 3607): ****************search UUID = 0100***********
W/bt-btif ( 3607): new conn_srvc id:26, app_id:255
W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3561): we got incoming connection
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3561): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/BTListenerThread( 3561): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3561): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3561): MESSAGE_WRITE 81 bytes.
I/HS      ( 3561): Incoming connection Hand Shake finished for : LGE-LG-D722_PT4379
I/BtConnectorHelper( 3561): Starting the connected thread incoming : true, LGE-LG-D722_PT4379
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3561): Creating BTConnectedThread
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3561): --DoOneRunRound started
,I/jxcore-log( 3561): 2015-12-01T22:10:49.879Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): LocalHost address: localhost/127.0.0.1, port: 34248
,I/BtToRequestSocket( 3561): --DoOneRunRound ended
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3607): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3607): Failed to remove device: F8:95:C7:87:85:54
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,D/BluetoothMetrics( 3607): btclass5a020c
,D/Checkin ( 3607): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3561): 2015-12-01T22:10:50.763Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:50.826Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:50.862Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:50.867Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:50.872Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3561): 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 16
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 16
,I/jxcore-log( 3561): 2015-12-01T22:10:50.930Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:50.964Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:50.977Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.008Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.015Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.025Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.027Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.063Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.077Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.114Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.119Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.124Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.136Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3561): 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 17 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 17 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:10:51.168Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.170Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.203Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.235Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:10:51.274Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3561): 
,W/bt-btif ( 3607): invalid rfc slot id: 14
,I/BtToSocketBase( 3561): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT4379
I/BtToSocketBase( 3561): Stop ReceivingThread
,I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Close LocalOutputStream
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3561): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3561): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT4379
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt socket
,I/BtToSocketBase( 3561): Close bt in
I/BtToSocketBase( 3561): Close bt out
,I/BtToSocketBase( 3561): Close bt socket
,I/jxcore-log( 3561): 2015-12-01T22:10:51.364Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3561): 
,W/bt-rfcomm( 3607): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3607): RFCOMM_DisconnectInd LCID:0x45
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 fa
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-30
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-37
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2,
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-6ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-15
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP b6:ce:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-38,
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,V/AlarmManager( 1019): sending alarm Alarm{446dee60 type 3 android}
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 17
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 17
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 18 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 18 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-34
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 82
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 11
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 11
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP fa:cf:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP fa:cf:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8212, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8212, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 3a:94:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 3a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 3a
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 18
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 18
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 19 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 19 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-48
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-27
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-10ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 13 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3561): Peer(10): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(11): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(12): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3561): Peer(13): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-28
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService( 1019): InactiveState{ when=-11ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-12ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -28 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 19
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 19
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 20 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 20 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 3a:94:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-37
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 fa
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 82:01:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-15
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-32,
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
,D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 36:fc:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT384, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT384, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP ee:1f:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,I/BtConnection( 3561): connectionTimeoutTimer
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3607): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:16, channel:-1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: Cancelled
,I/jxcore-log( 3561): 2015-12-01T22:11:29.844Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3561): 
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 16
,I/jxcore-log( 3561): 2015-12-01T22:11:29.845Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:29.849Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,W/jxcore-log( 3561): $$jxcore_callback_18 wasn't registered
W/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 20
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 20
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-34
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 21 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 21 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-47
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-6ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP ea:50:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP b6:ce:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 b6
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 b6
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:11:34.851Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:34.851Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-36
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:11:39.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:39.859Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:39.860Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:39.862Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3561): Connecting to G4-1, at F8:95:C7:87:3C:51
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[140]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 21
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 21
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139265 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 3561): Cleared service requests
I/        ( 3561): Started peer discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 22 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 22 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2,
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 13 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3561): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3561): Peer(9): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(10): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(11): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3561): Peer(12): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3561): Peer(13): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=59 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=59 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,W/bt-l2cap( 3607): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-14
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_1950
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -14 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3607): Entering PendingCommandState State
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3607): services_to_search = 3fffffff
,E/bt-btif ( 3607): ****************search UUID = 1200***********
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): services_to_search = 3ffffffe
,E/bt-btif ( 3607): ****************search UUID = 0100***********
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3561): Starting to Handshake
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3561): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-34
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2,
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,I/BTConnectToThread( 3561): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3561): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3561): HandshakeOk : LGE-LG-H815_PT5589
,I/HS      ( 3561): Hand Shake finished outgoing for : LGE-LG-H815_PT5589
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : false, LGE-LG-H815_PT5589
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): mHTTPPort  set to : 58870
,I/BtConnectorHelper( 3561): Request socket is using : 58870
,I/BtToRequestSocket( 3561): Now accepting connections
,I/BtConnectorHelper( 3561): Calling ConnectionStatusUpdate with port :58870
,I/jxcore-log( 3561): 2015-12-01T22:11:46.666Z SendDataConnector.js: CLIENT connected to 58870, error: null
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:46.668Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): incoming data from: /127.0.0.1, port: 58870
,I/BtToRequestSocket( 3561): Set local streams
,I/jxcore-log( 3561): 2015-12-01T22:11:46.681Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): rin ended ---------------------------;
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-38
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -38 target=com.android.internal.util.StateMachine$SmHandler }
V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1343): GC_EXPLICIT freed 911K, 38% free 10841K/17224K, paused 3ms+10ms, total 42ms
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 a2
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 a2
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 3 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb,
E/bt-btif ( 3607): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3607): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3607): Failed to remove device: F8:95:C7:87:3C:51
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,D/BluetoothMetrics( 3607): btclass1f00
,D/Checkin ( 3607): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-30
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 22
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 22
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 23 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 23 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-32
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 3a:94:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 fa
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ea
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 ea
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:11:56.751Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:56.752Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:56.754Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:56.756Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:11:56.758Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3561): 
,I/BtToSocketBase( 3561): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3561): Disconnect outgoing peer: LGE-LG-H815_PT5589
I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Close LocalOutputStream
I/BtToSocketBase( 3561): Close localHostSocket
,I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt socket
,I/BtToRequestSocket( 3561): Close server socket
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-31
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2,
,D/WifiP2pService( 1019): InactiveState{ when=-10ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,W/bt-btif ( 3607): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 92:b6:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4283de90 type 3 android}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 23
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 23
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 3a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 3a
,I/jxcore-log( 3561): 2015-12-01T22:12:01.758Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:01.759Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 24 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 24 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP ee:1f:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5589, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5589, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-32
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP fa:cf:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP fa:cf:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT8212","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT8212, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT8212, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP b6:ce:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP b6:ce:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:b6:ce:f6:ad:a4:6b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT5834"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT5834, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT5834, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3561): 2015-12-01T22:12:06.763Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:06.764Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:06.765Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:06.767Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3561): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[141]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 0a:ec:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-l2cap( 3607): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 24
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 24
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 25 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 25 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ea
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 ea
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-42
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2,
,D/WifiP2pService( 1019): InactiveState{ when=-10ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -42 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-rfcomm( 3607): PORT_StartCnf failed result:5
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3607): invalid rfc slot id: 19
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:3C:51 newState: 0
,E/BluetoothBondStateMachine( 3607): In stable state, received invalid newState: 10
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3561): 2015-12-01T22:12:12.798Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:12.798Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:12.798Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/bt-btif ( 3607): Do not find the bg connection mask for the remote device
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-48
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP a2:39:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT4379","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT4379, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT4379, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ea:50:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP ea:50:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ea:50:8b:de:28:a3 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2504","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT2504, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT2504, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:12:17.799Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:17.800Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 52
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 52
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 25
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 25
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 26 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 26 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:12:22.804Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:22.805Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:22.807Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:22.809Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3561): Connecting to G4-1, at F8:95:C7:87:3C:51
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[142]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
I/BluetoothBondStateMachine( 3607): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3607): Entering PendingCommandState State
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btif ( 3607): services_to_search = 3fffffff
,E/bt-btif ( 3607): ****************search UUID = 1200***********
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btif ( 3607): services_to_search = 3ffffffe
,E/bt-btif ( 3607): ****************search UUID = 0100***********
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3561): Starting to Handshake
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3561): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/BTConnectToThread( 3561): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3561): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5589","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3561): HandshakeOk : LGE-LG-H815_PT5589
I/HS      ( 3561): Hand Shake finished outgoing for : LGE-LG-H815_PT5589
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : false, LGE-LG-H815_PT5589
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): mHTTPPort  set to : 40777
,I/BtConnectorHelper( 3561): Request socket is using : 40777
,I/BtToRequestSocket( 3561): Now accepting connections
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 3 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3607): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3607): Failed to remove device: F8:95:C7:87:3C:51
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,D/BluetoothMetrics( 3607): btclass1f00
,D/Checkin ( 3607): publish the event [tag = MOT_BT event name = PAIRING]
,I/BtConnectorHelper( 3561): Calling ConnectionStatusUpdate with port :40777
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,I/jxcore-log( 3561): 2015-12-01T22:12:29.205Z SendDataConnector.js: CLIENT connected to 40777, error: null
I/jxcore-log( 3561): 
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3561): 2015-12-01T22:12:29.205Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): incoming data from: /127.0.0.1, port: 40777
,I/BtToRequestSocket( 3561): Set local streams
,I/BtToRequestSocket( 3561): rin ended ---------------------------;
,I/jxcore-log( 3561): 2015-12-01T22:12:29.214Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139265 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/WifiP2pService( 1019): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-3ms what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,I/SS      ( 3561): Found 14 peers.
,I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3561): Peer(3): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3561): Peer(4): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3561): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3561): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3561): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(8): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3561): Peer(9): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3561): Peer(10): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(11): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3561): Peer(12): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3561): Peer(13): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3561): Peer(14): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=64 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139301 arg2=64 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 26
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 26
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 27 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 27 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6174","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT6174, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT6174, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032 level=-36
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-37
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_63cc
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: WFD enabled: trueWFD DeviceInfo: 16
D/WifiP2pService( 1019):  WFD CtrlPort: 7236
D/WifiP2pService( 1019):  WFD MaxThroughput: 50
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 0a
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-27
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-9ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 3a:94:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 82:01:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 82:01:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:82:01:84:6b:e8:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9087, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9087, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-30
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -30 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 3561): 2015-12-01T22:12:39.270Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:39.270Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:39.272Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:39.283Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:39.283Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:39.284Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/BtConnectorHelper( 3561): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3561): Stop ReceivingThread
I/BtToSocketBase( 3561): Stop SendingThread
,I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3561): Close LocalOutputStream
,I/BtToSocketBase( 3561): Close localHostSocket
I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt socket
,I/BtToRequestSocket( 3561): Close server socket
,I/jxcore-log( 3561): 2015-12-01T22:12:39.290Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): ---- round done--------
I/jxcore-log( 3561): 
I/jxcore-log( 3561): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): do fake peer & start
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:39.293Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:12:39.293Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:39.294Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3561): Connecting to null, at 80:01:84:8A:B3:68
,I/jxcore-log( 3561): 2015-12-01T22:12:39.299Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3561): 
,I/chromium( 3561): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[143]}
,W/bt-btif ( 3607): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 92
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f2188a0 rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 27
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 27
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 28 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 28 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218c18 rs_disc_pending=1
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
I/BluetoothBondStateMachine( 3607): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3607): Entering PendingCommandState State
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3607): services_to_search = 3fffffff
,E/bt-btif ( 3607): ****************search UUID = 1200***********
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): services_to_search = 3ffffffe
,E/bt-btif ( 3607): ****************search UUID = 0100***********
,W/bt-btif ( 3607): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3607): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3561): Starting to Handshake
,I/BTHandshakeSocketThread( 3561): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3561): MESSAGE_WRITE 81 bytes.
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread started
,I/BTConnectToThread( 3561): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3561): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9087"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3561): HandshakeOk : HTC-HTC Desire 820_PT9087
I/HS      ( 3561): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9087
,I/BTHandshakeSocketThread( 3561): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3561): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9087
I/BtToSocketBase( 3561): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3561): mHTTPPort  set to : 53449
,I/BtConnectorHelper( 3561): Request socket is using : 53449
,I/BtToRequestSocket( 3561): Now accepting connections
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 3 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 4 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 5 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 6 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 7 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 8 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 9 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3607): Index: 10 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3607): Index: 11 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 3607): Index: 12 uuid:00006675-7475-7265-6469-616c62756d70
,I/BluetoothBondStateMachine( 3607): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3607): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3607): Failed to remove device: 80:01:84:8A:B3:68
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3607): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10,
,D/BluetoothMetrics( 3607): btclass1f00
,D/Checkin ( 3607): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 3607): StableState(): Entering Off State
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/BtConnectorHelper( 3561): Calling ConnectionStatusUpdate with port :53449
,I/jxcore-log( 3561): 2015-12-01T22:12:42.700Z SendDataConnector.js: CLIENT connected to 53449, error: null
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:42.701Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3561): 
,I/BtToRequestSocket( 3561): incoming data from: /127.0.0.1, port: 53449
,I/BtToRequestSocket( 3561): Set local streams
,I/BtToRequestSocket( 3561): rin ended ---------------------------;
,I/jxcore-log( 3561): 2015-12-01T22:12:42.719Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3561): 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,I/jxcore-log( 3561): 2015-12-01T22:12:43.364Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:43.438Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:43.537Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:43.614Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3561): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3561): 2015-12-01T22:12:43.742Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:43.806Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:43.907Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:43.951Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:44.043Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f218c18 rs_disc_pending=0
,W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=67 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-34
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=68 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 14 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(3): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 3561): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3561): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3561): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(8): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(10): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3561): Peer(11): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(12): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3561): Peer(13): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3561): Peer(14): Note3-1 ea:50:8b:de:28:a3
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=69 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139301 arg2=69 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,W/bt-btif ( 3607): dm_pm_timer expires
,W/bt-btif ( 3607): dm_pm_timer expires 0
,W/bt-btif ( 3607): proc dm_pm_timer expires
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 82
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 82
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=70 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-45
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-6ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 1019): GC_CONCURRENT freed 1798K, 64% free 18304K/50068K, paused 11ms+9ms, total 105ms
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-45
,D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 3607): invalid rfc slot id: 21
,I/BtToSocketBase( 3561): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3561): Disconnect outgoing peer: HTC-HTC Desire 820_PT9087
I/BtToSocketBase( 3561): Stop ReceivingThread
,I/BtToSocketBase( 3561): Stop SendingThread
I/BtToSocketBase( 3561): Close local in
,I/BtToSocketBase( 3561): Close LocalOutputStream
,I/BtToSocketBase( 3561): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3561): Close localHostSocket
I/BtToSocketBase( 3561): Close bt in
,I/BtToSocketBase( 3561): Close bt out
I/BtToSocketBase( 3561): Close bt socket
,I/BtToRequestSocket( 3561): Close server socket
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 28
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 28
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 29 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 29 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2,
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: Galaxy S5-2
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
,D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147477 obj=Device: G4-1
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 4488
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 36:fc:
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT384, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT384, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 3a:94:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 3a:94:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:3a:94:96:b5:06:dd version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/        ( 3561): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"}, typeCordovap2p._tcp.local.:
,I/        ( 3561): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT2917"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT2917, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT2917, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 a2
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 a2
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:12:54.043Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:54.044Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:54.046Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:54.047Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:54.049Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-34
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 7e:f9:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8736","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8736, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8736, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:12:59.049Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:59.050Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:12:59.052Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-37
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 92:b6:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 7e
,V/AlarmManager( 1019): sending alarm Alarm{4283f890 type 3 android}
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-46
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 29
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 29
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 30 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 30 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:13:04.056Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:04.057Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:04.058Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:04.060Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3561): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[144]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-sdp  ( 3607): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 22
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:13:09.283Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:09.284Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:09.288Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:09.289Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139307 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=71 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139265 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=72 target=com.android.internal.util.StateMachine$SmHandler }
I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-24
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2,
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=0 what=139283 arg2=73 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=74 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 12 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3561): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3561): Peer(8): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(9): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3561): Peer(10): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3561): Peer(11): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3561): Peer(12): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=75 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=75 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-28
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=76 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 30
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 30
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-37
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 31 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 31 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -37 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 92:b6:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test's G2
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 3561): 2015-12-01T22:13:14.292Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:14.293Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:14.295Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 36:fc:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 36:fc:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:36:fc:ef:de:0a:e2 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT384"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT384, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT384, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6
D/WifiP2pService( 1019): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: b6:ce:f6:ad:a4:6b
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:13:19.299Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:19.300Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:19.303Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:19.305Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3561): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[145]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 31
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 31
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 32 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 32 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-sdp  ( 3607): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 23
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:13:24.511Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:24.512Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:24.514Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:24.515Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-31
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_50a5
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-41
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: Note3-1
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -41 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=77 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139265 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=78 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=0 what=139283 arg2=79 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 10 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(3): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3561): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3561): Peer(5): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3561): Peer(6): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3561): Peer(7): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(8): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3561): Peer(9): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3561): Peer(10): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=80 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139301 arg2=80 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139310 arg2=81 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 3561): 2015-12-01T22:13:29.517Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:29.518Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:29.519Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=3a:94:96
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=3a:94:96
,D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=82:01:84
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=82:01:84
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 3a:94:96:b5:06:dd
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 82:01:84:6b:e8:5d
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: n,ull
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 32
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 32
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 33 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 33 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP ee:1f:
D/WifiP2pService( 1019): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3584","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3584, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3584, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:13:34.523Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:34.524Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:34.525Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:34.526Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3561): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[146]}
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-27
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-3ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [80:01:84:8a:b3:68]: 7, f, 6109
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 24
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:13:36.200Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:36.204Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:13:36.204Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:36.205Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 34 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 34 3
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 92
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 33
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 33
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 35 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 35 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:13:41.208Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:41.210Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:41.211Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 44
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 44
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=82 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=83 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-27
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2,
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=84 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=85 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 6 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3561): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3561): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3561): Peer(5): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3561): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=86 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139301 arg2=86 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=87 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:13:46.219Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:46.220Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:46.221Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:46.223Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3561): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[147]}
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-25
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -25 target=com.android.internal.util.StateMachine$SmHandler }
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 25
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3561): 2015-12-01T22:13:47.598Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:13:47.599Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:47.599Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:47.601Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:47.605Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:47.606Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:13:47.607Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): ---- round done--------
I/jxcore-log( 3561): 
I/jxcore-log( 3561): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3561): 
I/jxcore-log( 3561): do fake peer & start
I/jxcore-log( 3561): 
I/jxcore-log( 3561): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:47.609Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:13:47.609Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:47.609Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3561): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
I/chromium( 3561): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[148]}
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/MediatorProvider( 4391): Constructor
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,E/bt-btm  ( 3607): tBTM_SEC_DEV:0x5f2181b0 rs_disc_pending=1
W/bt-btif ( 3607): bta_dm_check_av:0
,W/bt-btif ( 3607): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 26
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:13:50.027Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:50.029Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:50.030Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:50.032Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 35
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 35
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 36 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 36 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:13:55.034Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:55.035Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:13:55.036Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-36
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 92:b6:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2405","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2405, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2405, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 44
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 44
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,V/AlarmManager( 1019): sending alarm Alarm{430e8f58 type 3 android}
,I/jxcore-log( 3561): 2015-12-01T22:14:00.047Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:00.048Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:00.049Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:00.051Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820,
I/        ( 3561): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[149]}
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef
D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: fa:cf:c5:d9:e5:62
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-11ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 36:fc:ef:de:0a:e2
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-19ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: ea:50:8b:de:28:a3
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 36
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 36
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 37 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 37 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 27
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:14:04.582Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:04.583Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:04.583Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:04.583Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=88 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139265 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=89 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-40
,D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2,
,D/WifiP2pService( 1019): InactiveState{ when=-7ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147477 obj=Device: S5-1
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=90 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=91 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 3 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3561): Peer(2): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3561): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=92 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=92 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139310 arg2=93 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/jxcore-log( 3561): 2015-12-01T22:14:09.588Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:09.589Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:09.591Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-11ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-11ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 37
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 37
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 38 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 38 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 39 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 39 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:14:14.596Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:14.597Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:14.598Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:14.600Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3561): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[150]}
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 28
I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3561): 2015-12-01T22:14:14.879Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:14.879Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:14.880Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:14.880Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/dalvikvm( 3607): GC_EXPLICIT freed 2032K, 45% free 9556K/17224K, paused 1ms+6ms, total 35ms
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:14:19.880Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:19.880Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:19.881Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 38
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 38
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 40 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 40 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:14:24.885Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:24.886Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:24.888Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:24.889Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3561): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[151]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 29
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:14:27.656Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:27.657Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:27.657Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:27.658Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 40
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 40
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 41 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 41 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:14:32.661Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:32.661Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:32.662Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139307 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=94 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=95 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:14:37.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.666Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.667Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.669Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3561): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 30
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:14:37.851Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:37.851Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.852Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.868Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.868Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.870Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): ---- round done--------
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): do fake peer & start
I/jxcore-log( 3561): 
I/jxcore-log( 3561): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.876Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:37.877Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:37.877Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[153]}
I/        ( 3561): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
,I/chromium( 3561): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 31
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3561): 2015-12-01T22:14:39.343Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:39.343Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:39.344Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:39.345Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-8ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=96 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 2 peers.
I/SS      ( 3561): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3561): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=97 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=97 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 41
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 41
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=98 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 42 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 42 c
I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-21
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -21 target=com.android.internal.util.StateMachine$SmHandler }
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3561): 2015-12-01T22:14:44.347Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:44.348Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:44.349Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/wpa_supplicant( 3679): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
,D/MDMCTBK (  273): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/WifiP2pService( 1019): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService( 1019):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService( 1019):  primary type: null
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 0
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 0
D/WifiP2pService( 1019):  status: 4
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:14:49.353Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:49.354Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:49.355Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:49.356Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,I/        ( 3561): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 42
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 42
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [34:fc:ef:11:ae:67]: 7, 1d, 7d3
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 32
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:14:51.045Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:51.046Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:14:51.046Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:51.046Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 43 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 43 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=99 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139265 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139265 arg2=100 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:14:56.053Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:56.070Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:14:56.070Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{43cbe7e0 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-9ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139283 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139283 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=101 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 1 peers.
,I/SS      ( 3561): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=102 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=102 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 44 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 44 0
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=103 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-11ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-11ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,V/AlarmManager( 1019): sending alarm Alarm{428b35e0 type 3 android}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 43
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 43
,V/AlarmManager( 1019): sending alarm Alarm{4278a328 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{4278a400 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5088 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/jxcore-log( 3561): 2015-12-01T22:15:01.071Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:01.071Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:15:01.072Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:01.072Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3561): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[155]}
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 45 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 45 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 33
I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:15:01.800Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:15:01.801Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:15:01.801Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:01.801Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:06.802Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:06.803Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:06.804Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 45
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 45
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 46 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 46 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:11.809Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:11.810Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:11.811Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:11.813Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,I/        ( 3561): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[156]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 34
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3561): 2015-12-01T22:15:13.273Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:15:13.274Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:13.274Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:13.274Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 39
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 39
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-5ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/dalvikvm( 1019): GC_EXPLICIT freed 1660K, 64% free 18350K/50068K, paused 4ms+11ms, total 96ms
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 47 f
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 47 f
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:18.282Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:18.282Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:18.282Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 46
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 46
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 48 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 48 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:23.285Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:23.285Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:23.287Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:23.288Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 34:FC:EF:11:AE:67, name: Nexus 5
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/        ( 3561): Connecting to Nexus 5, at 34:FC:EF:11:AE:67
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[157]}
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 35
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:15:24.228Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:15:24.228Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:24.228Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:24.232Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:24.233Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:24.235Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3561): 
I/jxcore-log( 3561): ---- round done--------
I/jxcore-log( 3561): 
I/jxcore-log( 3561): ---- gotta redo : 34:FC:EF:11:AE:67, try count now: 1
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): do fake peer & start
I/jxcore-log( 3561): 
I/jxcore-log( 3561): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:24.236Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:15:24.237Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:24.238Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/BTConnectToThread( 3561): Starting to connect
,I/        ( 3561): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/chromium( 3561): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:AE:67 done with result: Connection to 34:FC:EF:11:AE:67 failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[158]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 36
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:15:27.009Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:27.010Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:27.012Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:27.014Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139307 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=104 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=105 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests,
,I/        ( 3561): Started peer discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-8ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=106 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 1 peers.
,I/SS      ( 3561): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=107 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139301 arg2=107 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4391): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3607): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3607): Ftp Service onStartCommand
,V/BluetoothFtpService( 3607): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/BluetoothAdapterService(1106493456)( 3607): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3607): getBondedDevices: length=1
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139310 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=108 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-29
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -29 target=com.android.internal.util.StateMachine$SmHandler }
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-27
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-9ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -27 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 48
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 48
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 49 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 49 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:32.015Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:32.016Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:32.017Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
,I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online,
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open '',
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:37.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:37.022Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:15:37.024Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:37.025Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3561): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[159]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 37
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:15:39.363Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:39.365Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:39.366Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:39.368Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 49
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 49
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 50 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 50 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:44.370Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:44.371Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:44.372Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:f4:6f:30:e0:6d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/        ( 3561): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"}, typeCordovap2p._tcp.local.:
I/        ( 3561): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8573"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT8573, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3561): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT8573, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:49.377Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:49.378Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:49.379Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:49.381Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3561): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[160]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 38
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:15:50.071Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:50.072Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:50.074Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:50.075Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 50
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 50
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 51 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 51 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 52 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 52 0
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:15:55.078Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:55.079Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:15:55.080Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 02
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-REQ 2462 02
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139307 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139307 arg2=109 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState clear service request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139265 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=139265 arg2=110 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3561): Cleared service requests
,I/        ( 3561): Started peer discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-22
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-10ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-10ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=0 what=139283 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=139283 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=139283 arg2=111 target=com.android.internal.util.StateMachine$SmHandler }
I/SS      ( 3561): Found 1 peers.
,I/SS      ( 3561): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019): InactiveState{ when=0 what=139301 arg2=112 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139301 arg2=112 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 3561): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3561): Added service request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=139310 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=139310 arg2=113 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,I/        ( 3561): Started service discovery
,I/wpa_supplicant( 3679): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 level=-25
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/MDMCTBK (  273): Event received = P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5mini-1
D/WifiP2pService( 1019):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiP2pService( 1019):  primary type: 10-0050F204-5
D/WifiP2pService( 1019):  secondary type: null
D/WifiP2pService( 1019):  wps: 392
D/WifiP2pService( 1019):  grpcapab: 0
D/WifiP2pService( 1019):  devcapab: 37
D/WifiP2pService( 1019):  status: 3
D/WifiP2pService( 1019):  wfdInfo: null
D/WifiP2pService( 1019):  level: -25 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,V/AlarmManager( 1019): sending alarm Alarm{43d0ddc0 type 3 android}
,I/jxcore-log( 3561): 2015-12-01T22:16:00.082Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:00.082Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:16:00.083Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:00.083Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3561): Connecting to null, at 7C:F9:0E:34:8A:A0
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[161]}
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 39
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:16:00.588Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:16:00.588Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:16:00.589Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:00.589Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 51
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 51
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 53 c
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 53 c
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:16:05.589Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:05.590Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:05.592Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 54 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 54 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 55 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 55 0
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:16:10.596Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:10.597Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:10.598Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:10.600Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3561): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[162]}
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 53
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 53
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 56 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 56 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3607): invalid rfc slot id: 40
I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:16:12.005Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:16:12.005Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:12.006Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:12.014Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:12.015Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:12.016Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3561): 
I/jxcore-log( 3561): ---- round done--------
I/jxcore-log( 3561): 
I/jxcore-log( 3561): ---- gotta redo : 7C:F9:0E:34:8A:A0, try count now: 1
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): do fake peer & start
I/jxcore-log( 3561): 
I/jxcore-log( 3561): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:16:12.018Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:12.018Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:12.018Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3561): Connecting to null, at 08:EC:A9:50:75:41
I/chromium( 3561): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: Connection to 7C:F9:0E:34:8A:A0 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[163]}
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 41
I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:16:12.518Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:16:12.518Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:16:12.519Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:12.519Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:f4:
,D/MDMCTBK (  273): Event received = P2P-SERV-DISC-RESP 02:f4:
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147494 obj=[] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 34
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 34
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3561): 2015-12-01T22:16:17.520Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:17.521Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:17.521Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 56
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 56
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 57 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 57 c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 58 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 58 0
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 47
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 47
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:16:22.524Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:22.525Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3561): 
I/jxcore-log( 3561): 2015-12-01T22:16:22.526Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:22.527Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3561): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[164]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
,D/        ( 3607): remote version info [08:ec:a9:50:75:41]: 7, f, 610c
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 42
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:16:23.848Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:23.849Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:23.851Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:23.853Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:16:28.855Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:28.856Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:28.857Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 57
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 57
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 59 c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 59 c
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,I/jxcore-log( 3561): 2015-12-01T22:16:33.864Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:33.864Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:33.866Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:33.867Z SendDataConnector.js: do connect now
I/jxcore-log( 3561): 
,I/        ( 3561): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3561): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3561): Starting to connect
,W/BluetoothAdapter( 3561): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3607): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 3561): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[165]}
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,W/bt-btif ( 3607): info:x10
D/        ( 3607): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3607): process_service_search_attr_rsp
,E/bt-btif ( 3607): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3607): invalid rfc slot id: 43
,I/BTConnectToThread( 3561): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3561): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3561): 2015-12-01T22:16:34.066Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:34.067Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:34.069Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3561): 
,I/jxcore-log( 3561): 2015-12-01T22:16:34.069Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3561): 
,D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 60 a
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 60 a
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
,D/TCMD    (  387): Listening for incoming client connection request
,TIME-OUT KILL (timeout was 600000ms),D/AndroidRuntime( 5178): 
D/AndroidRuntime( 5178): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5178): CheckJNI is OFF
D/dalvikvm( 5178): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5178): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5178): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5178): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5178): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5178): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
D/btif_config_util( 3607): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
E/memtrack( 5178): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5178): failed to load memtrack module: -2
D/AndroidRuntime( 5178): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10421 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3561:com.test.thalitest/u0a421 (adj 9): stop com.test.thalitest
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{44542ab0 u0 com.test.thalitest/.MainActivity t3}
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WindowState( 1019): WIN DEATH: Window{4454f350 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1019): Client connection lost with reason: 4
E/bt-btif ( 3607): bta_jv_rfcomm_stop_server
W/PackageSettings( 1019): Skipping PackageSetting{421e75a0 com.example.hello/10416} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10421 user=0: pkg removed
D/dalvikvm( 1292): GC_EXPLICIT freed 2895K, 33% free 11593K/17224K, paused 2ms+13ms, total 44ms
D/dalvikvm( 2210): GC_EXPLICIT freed 3612K, 42% free 10081K/17224K, paused 2ms+4ms, total 80ms
I/Launcher( 1292): Deferring update until onResume
W/GeofencerStateMachine( 1199): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2178): GC_EXPLICIT freed 6600K, 44% free 9778K/17224K, paused 7ms+7ms, total 60ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/VoicemailCleanupService( 4280): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1019): GC_EXPLICIT freed 1041K, 64% free 18224K/50068K, paused 5ms+18ms, total 137ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449008197
I/Launcher( 1292): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/InternalIcingCorporaPro( 2210): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5208 uid=10059 gids={50059, 3003, 1028, 1015}
D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449008197
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10421 #1
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
D/dalvikvm( 1019): GC_EXPLICIT freed 550K, 64% free 18167K/50068K, paused 6ms+15ms, total 203ms
I/InternalIcingCorporaPro( 2210): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
D/AndroidRuntime( 5178): Shutting down VM
D/dalvikvm( 5178): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
D/TCMD    (  387): NL - Read 56 bytes from update socket.
D/TCMD    (  387): NL - message type is RTM_NEWLINK
D/TCMD    (  387): Listening for incoming client connection request
W/ActiveOrDefaultContextProvider( 5208): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5230 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1019): Killing 4243:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1242): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/GAV2    ( 5208): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 5230): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1381): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1381): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1381): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1381): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1381): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1381): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1381): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1343): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1343): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
E/SQLiteLog( 1381): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1381): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1381): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1381): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1381): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1381): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1381): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1381): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1381): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1381): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1381): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1381): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1381): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1381): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1381): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1381): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1381): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1381): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1381): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1381): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1381): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1381): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1381): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1381): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1381): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1381): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1381): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1381): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1381): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1381): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1381): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1381): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1381): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1381): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1381): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1381): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1381): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1381): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1381): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1381): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1381): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1381): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1381): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1381): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1381): disk I/O error (code 3850)
E/DriveAsyncService( 1381): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1381): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1381): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1381): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1381): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1381): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1381): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1381): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1381): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1381): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1381): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1381): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1381): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1381): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1381): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1381): 	at java.lang.Thread.run(Thread.java:841)
W/SQLiteOpenHelper( 1381): Opened phenotype.db in read-only mode
W/SQLiteOpenHelper( 1381): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1381): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1381): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/ClearPendingStateOp( 1381): Runtime exception while performing operation
E/ClearPendingStateOp( 1381): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1381): 	at com.google.android.gms.common.i.a.b(SourceFile:283)
E/ClearPendingStateOp( 1381): 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1381): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 1381): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/ClearPendingStateOp( 1381): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1381): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1381): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 1381): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1381): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1381): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1381): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1381): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1381): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1381): threadid=49: thread exiting with uncaught exception (group=0x41656d40)
F/ClearPendingStateOp( 1381): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1381): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1381): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1381): 	at com.google.android.gms.common.i.a.b(SourceFile:283)
F/ClearPendingStateOp( 1381): 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1381): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 1381): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
F/ClearPendingStateOp( 1381): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1381): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1381): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 1381): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1381): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1381): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1381): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1381): (3850) statement aborts at 26: [DELETE FROM events WHERE app_id=?] disk I/O error
E/GMPM-SVC( 1381): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5261 uid=10058 gids={50058}
E/SharedPreferencesImpl( 1381): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
W/FileUtils( 1381): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): Can't write: system_app_wtf
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 5 more
E/GAv4-SVC( 1381): Error creating clientId file: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/gaClientId: open failed: EROFS (Read-only file system)
E/SharedPreferencesImpl( 1381): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1381): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1381): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
I/Icing   ( 1381): doRemovePackageData com.test.thalitest
E/SharedPreferencesImpl( 1381): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5230): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5230): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5230): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5230): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5230): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5230): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5230): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5230): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5230): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5230): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5230): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5230): threadid=10: thread exiting with uncaught exception (group=0x41656d40)
E/bt-btm  ( 3607): btm_sec_disconnected - Clearing Pending flag
I/dalvikvm( 4318): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4318): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4318): VFY: replacing opcode 0x6e at 0x0013
E/BluetoothRemoteDevices( 3607): aclStateChangeCallback: Device is NULL
E/GAv4-SVC( 1381): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1381): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/PeopleContactsSync( 1381): CP2 sync disabled
E/AndroidRuntime( 5230): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5230): Process: com.android.keychain, PID: 5230
E/AndroidRuntime( 5230): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5230): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5230): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5230): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5230): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5230): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5230): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5230): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5230): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5230): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 5230): Sending signal. PID: 5230 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 5 more
I/ActivityManager( 1019): Process com.android.keychain (pid 5230) has died.
W/ActivityManager( 1019): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
E/SQLiteLog( 1381): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1381): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1381): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AndroidRuntime( 1381): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1381): Process: com.google.android.gms, PID: 1381
E/AndroidRuntime( 1381): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1381): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1381): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 1381): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 1381): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1381): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1381): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 5 more
I/Process ( 1381): Sending signal. PID: 1381 SIG: 9

```
