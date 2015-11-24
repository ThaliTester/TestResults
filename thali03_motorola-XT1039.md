#### Test 515172835a91168_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 1326): GC_EXPLICIT freed 913K, 39% free 10557K/17224K, paused 3ms+5ms, total 36ms
--------- beginning of /dev/log/system
W/SocketClient(  271): write error (Broken pipe)
D/AndroidRuntime( 3487): 
D/AndroidRuntime( 3487): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3487): CheckJNI is OFF
D/dalvikvm( 3487): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3487): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3487): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3487): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3487): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3487): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3487): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3487): failed to load memtrack module: -2
D/AndroidRuntime( 3487): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3487
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3505 uid=10407 gids={50407, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3487): Shutting down VM
D/dalvikvm( 3487): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 17ms
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
V/WebViewChromiumFactoryProvider( 3505): Binding Chromium to main looper Looper (main, tid 1) {41fa2990}
I/LibraryLoader( 3505): Expected native library version number "",actual native library version number ""
I/chromium( 3505): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3505): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@432bb148:true
D/BluetoothAdapter( 3505): 1106997152: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3505): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3505): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3505): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3505): Local Branch: 
I/Adreno-EGL( 3505): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3505): Local Patches: NONE
I/Adreno-EGL( 3505): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3505): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3505): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3505): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3505): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3505): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3505): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3505): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3505): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3505): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3505): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3505): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3505): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3505): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3505): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3505): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3505): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3505): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3505): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3505): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3505): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3505): Enabling debug mode 0
,W/AwContents( 3505): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3505): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,403
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +369ms (total +403ms)
,D/JsMessageQueue( 3505): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3505): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fa6e40
,D/dalvikvm( 3505): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fa6e40
,D/jxcore_app_log( 3505): JniHelper::setJavaVM(0x415eefa8), pthread_self() = 1614805200
,D/JX-Cordova( 3505): jxcore cordova android initializing
,I/dalvikvm( 3505): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 3505): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3505): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3505): GC_CONCURRENT freed 2907K, 18% free 14282K/17224K, paused 2ms+2ms, total 45ms
,D/dalvikvm( 3505): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 2K, 18% free 14282K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3505): Grow heap (frag case) to 16.073MB for 98002-byte allocation
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 216K, 18% free 14282K/17320K, paused 28ms, total 30ms
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 256K, 18% free 14330K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3505): Grow heap (frag case) to 16.237MB for 220492-byte allocation
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 373K, 18% free 14406K/17536K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3505): Grow heap (frag case) to 16.416MB for 330734-byte allocation
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 579K, 19% free 14530K/17860K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3505): Grow heap (frag case) to 16.695MB for 496096-byte allocation
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 880K, 20% free 14709K/18348K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3505): Grow heap (frag case) to 17.106MB for 744140-byte allocation
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 1301K, 22% free 14970K/19076K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3505): Grow heap (frag case) to 17.715MB for 1116206-byte allocation
,D/dalvikvm( 3505): GC_CONCURRENT freed 1735K, 24% free 15356K/20168K, paused 1ms+4ms, total 34ms
,D/dalvikvm( 3505): GC_CONCURRENT freed 1606K, 22% free 15868K/20168K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 3505): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 1799K, 21% free 16014K/20168K, paused 31ms, total 31ms
,I/dalvikvm-heap( 3505): Grow heap (frag case) to 20.066MB for 2511452-byte allocation
,D/dalvikvm( 3505): GC_CONCURRENT freed 285K, 19% free 18354K/22624K, paused 4ms+5ms, total 50ms
,D/dalvikvm( 3505): GC_CONCURRENT freed 4426K, 26% free 16948K/22624K, paused 3ms+7ms, total 41ms
,D/dalvikvm( 3505): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/dalvikvm-heap( 3505): Grow heap (frag case) to 22.176MB for 3767174-byte allocation
,D/dalvikvm( 3505): GC_CONCURRENT freed 341K, 23% free 20462K/26304K, paused 4ms+4ms, total 37ms
,D/dalvikvm( 3505): GC_FOR_ALLOC freed 2922K, 32% free 17909K/26304K, paused 27ms, total 27ms
,W/jxcore-log( 3505): Initializing JXcore engine
,W/jxcore-log( 3505): JXcore engine is ready
,D/dalvikvm( 3505): GC_CONCURRENT freed 351K, 22% free 20517K/26304K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 3505): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 3505): Starting JXcore engine
,W/jxcore-log( 3505): Platform android
W/jxcore-log( 3505): 
,W/jxcore-log( 3505): Process ARCH arm
W/jxcore-log( 3505): 
,I/jxcore-log( 3505): JXcore Cordova bridge is ready!
I/jxcore-log( 3505): 
,W/jxcore-log( 3505): JXcore engine is started
,I/chromium( 3505): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3505): Turning radios to true
I/jxcore-log( 3505): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1018): Message: 1
,W/Settings( 1259): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService( 1018): MESSAGE_ENABLE: mBluetooth = null
,I/jxcore-log( 3505): toggleBluetooth - 
I/jxcore-log( 3505): 
D/WifiService( 1018): New client listening to asynchronous messages
D/WifiService( 1018): setWifiEnabled: true pid=3505, uid=10407
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,I/ActivityManager( 1018): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3560 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/XTWiFiOS( 1267): Active network info is not available
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1259): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1259): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1018): setting operational mode to 1
D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
D/WifiStateMachine( 1018): processMsg: InitialState
,D/WifiStateMachine( 1018): processMsg: DefaultState
I/jxcore-log( 3505): toggleWiFi
I/jxcore-log( 3505): 
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1018): processMsg: InitialState
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1259): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1267): Active network info is not available
,D/AdapterServiceConfig( 3560): Adding HeadsetService
D/AdapterServiceConfig( 3560): Adding A2dpService
D/AdapterServiceConfig( 3560): Adding HidService
D/AdapterServiceConfig( 3560): Adding HealthService
D/AdapterServiceConfig( 3560): Adding PanService
D/AdapterServiceConfig( 3560): Adding GattService
,D/AdapterServiceConfig( 3560): Adding BluetoothMapService
,D/BluetoothAdapterService( 3560): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1018): Message: 20
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43dc2518:true
,D/BluetoothAdapterState( 3560): make
,I/BluetoothAdapterState( 3560): Entering OffState
,I/bluedroid( 3560): init
,I/bte_conf( 3560): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3560): get_profile_interface socket
,D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1018): Message: 40
,D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/GKI_LINUX( 3560): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3560): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:1 len:6
I/bluedroid( 3560): config_hci_snoop_log
,D/BluetoothAdapterProperties( 3560): Name is: XT1039
,D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
D/BluetoothManagerService( 1018): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterState( 3560): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3560): Setting state to 11
I/BluetoothAdapterState( 3560): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3560): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothBondStateMachine( 3560): make
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3560): StableState(): Entering Off State
,I/ActivityManager( 1018): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3597 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1018): Proxy object connected
D/BluetoothHeadset( 1247): Proxy object connected
D/BluetoothHeadset( 1247): Proxy object connected
D/BluetoothHeadset( 1247): Proxy object connected
D/HeadsetService( 3560): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3560): classInitNative: succeeds
D/HeadsetStateMachine( 3560): Version 1.6
D/HeadsetStateMachine( 3560): make
I/BluetoothAdapterState( 3560): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/bluedroid( 3560): get_profile_interface handsfree
,D/BluetoothA2dp( 1018): Proxy object connected
,D/A2dpService( 3560): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3560): classInitNative: succeeds
V/Avrcp   ( 3560): make
,I/bluedroid( 3560): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3560): classInitNative: succeeds
D/A2dpStateMachine( 3560): make
,I/bluedroid( 3560): get_profile_interface a2dp
,I/GKI_LINUX( 3560): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3560): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3560): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3560): classInitNative: succeeds
,D/HidService( 3560): Received start request. Starting profile...
,I/bluedroid( 3560): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3560): classInitNative: succeeds
,D/HealthService( 3560): Received start request. Starting profile...
,I/bluedroid( 3560): get_profile_interface health
,I/BluetoothPanServiceJni( 3560): classInitNative(L105): succeeds
,D/BluetoothPan( 1018): BluetoothPAN Proxy object connected
D/PanService( 3560): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3560): initializeNative(L110): pan
,I/bluedroid( 3560): get_profile_interface pan
,D/BluetoothTethering( 1018): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothTethering( 1018): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43d9d258
,I/BtGatt.JNI( 3560): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3560): handleDebugAction() action=null
D/BtGatt.GattService( 3560): Received start request. Starting profile...
D/BtGatt.GattService( 3560): start()
,I/bluedroid( 3560): get_profile_interface gatt
I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is add
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
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
,E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/TCMD    (  444): NL - Read 1004 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
,D/TCMD    (  444): Listening for incoming client connection request
,D/Tethering( 1018): InitialState.processMessage what=4
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
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
,E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  444): NL - Read 1004 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
,D/TCMD    (  444): Listening for incoming client connection request
,D/BluetoothMapService( 3560): Received start request. Starting profile...
,D/BluetoothMapService( 3560): start()
,D/HeadsetPhoneState( 3560): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3560): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3560): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3560): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3560): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3560): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3560): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3560): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/HeadsetPhoneState( 3560): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 3560): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3560): enable
D/QsoftapCmd(  271): Got softap fwreload command we are passing on
,D/SoftapController(  271): Softap fwReload - Ok
I/bt_hci_bdroid( 3560): init
I/bt_vendor( 3560): bt-vendor : init
I/bt_hci_bdroid( 3560): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3560): userial_init
I/bt_hwcfg( 3560): Starting hciattach daemon
I/bt_hwcfg( 3560): try to set false
I/ActivityManager( 1018): Killing 3193:com.android.providers.calendar/u0a8 (adj 15): empty #9
I/bt_hwcfg( 3560): Starting hciattach daemon
I/bt_hwcfg( 3560): try to set true
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/bt_hci_bdroid( 3560): bt_hc_worker_thread started
,D/WifiService( 1018): New client listening to asynchronous messages
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring down wlan0
I/qcom-bluetooth( 3624): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/WifiHW  ( 1018): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1018): ctrl_interface != /data/misc/wifi/sockets
,D/WifiStateMachine( 1018): setWifiState: enabling
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1267): Active network info is not available
,D/WifiStateMachine( 1018): Supplicant start successful
,D/WifiMonitor( 1018): startMonitoring(wlan0) with mConnected = false
,I/qcom-bluetooth( 3633): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3634): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,V/BluetoothFtpReceiver( 3560): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,I/qcom-bluetooth( 3636): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/wpa_supplicant( 3631): Successfully initialized wpa_supplicant
,I/qcom-bluetooth( 3637): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/wpa_supplicant( 3631): rfkill: Cannot open RFKILL control device
,D/AuthorizationBluetoothService( 1326): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/TCMD    (  444): NL - Read 1000 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/TCMD    (  444): Listening for incoming client connection request
D/TCMD    (  444): NL - Read 1000 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
,D/TCMD    (  444): Listening for incoming client connection request
,I/qcom-bluetooth( 3638): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/Diag_Lib( 3640): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3640): Setting internal use port to rmnet0
E/Diag_Lib( 3640):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3640): Failed on DIAG init
E/Diag_Lib( 3640): linux_qmi_qmux_if_client_get_proc_name: pid=3640, proc_name=hci_qcomm_init
E/Diag_Lib( 3640): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3640): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3640): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3640): qmi_client [3640]: successfully connected to server, attempt=1
E/Diag_Lib( 3640): linux_qmi_qmux_if_client_get_client_id [3640]: qmux_client_id=13
E/Diag_Lib( 3640): qmi_client [3640] 13: qmux_client ID is initialized
E/Diag_Lib( 3640): qmi_client [3640] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3640): qmi_client [3640] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3640): qmi_client [3640] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3640): Sending signal ...... to read cmd data 
E/Diag_Lib( 3640): qmi error code.........:0
E/Diag_Lib( 3640): qmi sys error code.........:0
E/Diag_Lib( 3640): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3640): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3640): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3640): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3640): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3640): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3640): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3640): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3640): qmi_init:  Created client handle b8d78788
,E/Diag_Lib( 3640): qmi_client [3640] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3640): qmi_client [3640] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3640): Sending signal ...... to read cmd data 
E/Diag_Lib( 3640): qmi error code.........:0
,E/Diag_Lib( 3640): qmi sys error code.........:0
E/Diag_Lib( 3640): Setting the api flag to : 1
,E/Diag_Lib( 3640): qmi_client [3640] 13: sending 54 bytes on fd = 8
,E/Diag_Lib( 3631): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3631): Setting internal use port to rmnet0
,E/wpa_supplicant( 3631): baseband property is set to [msm]
,I/rmt_storage(  411): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7ae21d0
I/rmt_storage(  411): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  411): wakelock acquired: 1, error no: 42
,I/rmt_storage(  411): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1213324744)
E/Diag_Lib( 3640): qmi_client [3640] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3640):  API Flag .............. 1 
,E/Diag_Lib( 3640):  Message ID ............... 92 
,E/wpa_supplicant( 3631):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3631): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3631): card_info[i].card_state: 0x2
E/wpa_supplicant( 3631): card_info[i].error_code: 0x3
E/wpa_supplicant( 3631): SIM/USIM not ready
,E/wpa_supplicant( 3631): Error while reading SIM card status
,E/wpa_supplicant( 3631): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3631): card_info[i].card_state: 0x2
E/wpa_supplicant( 3631): card_info[i].error_code: 0x3
E/wpa_supplicant( 3631): SIM/USIM not ready
,I/wpa_supplicant( 3631): eap_proxy: Card not ready
,E/Diag_Lib( 3640): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3640): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3640): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3640): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3640): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3640): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3640): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3640): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3640): qmi_client [3640] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3640): qmi_client [3640] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3640): Sending signal ...... to read cmd data 
E/Diag_Lib( 3640): qmi error code.........:0
E/Diag_Lib( 3640): qmi sys error code.........:0
E/Diag_Lib( 3640): qmi_release: Released client handle ff
E/Diag_Lib( 3640): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3640): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3640): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3640): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3640): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3640): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3640): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3640): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3640): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3640): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3640): qmi_client [3640] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3640): qmi_client [3640] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3640): Sending signal ...... to read cmd data 
E/Diag_Lib( 3640): qmi error code.........:0
E/Diag_Lib( 3640): qmi sys error code.........:0
E/Diag_Lib( 3640): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3640] 13
E/Diag_Lib( 3640): qmi_client [3640] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3640): qmi_client [3640] 13: failed to locate client data
E/Diag_Lib( 3640): qmi_client [3640] 13: calling release of fd=8
,E/Diag_Lib( 3640): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,I/rmt_storage(  411): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  411): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  411): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1213324744) wakelock released: 1, error no: 0
I/rmt_storage(  411): 
,I/rmt_storage(  411): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7ae21d0
,I/wpa_supplicant( 3631): Long line in configuration file truncated
,D/Checkin ( 2135): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/wpa_supplicant( 3631): rfkill: Cannot open RFKILL control device
D/TCMD    (  444): NL - Read 1000 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
,D/TCMD    (  444): Listening for incoming client connection request
,D/Checkin ( 2135): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/qcom-bluetooth( 3644): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3645): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3560): bluetooth satus is on
,D/bt_userial_mct( 3560): userial_open(port:0)
I/GKI_LINUX( 3560): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3560): btu_task pending for preload complete event
I/bt_userial_vendor( 3560): Done intiailizing UART
I/bt_userial_vendor( 3560): Done intiailizing UART
I/bt_userial_mct( 3560): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3560): Bluetooth Firmware and smd is initialized
,D/bt_userial_mct( 3560): Entering userial_read_thread()
I/bt-btu  ( 3560): btu_task received preload complete event
,E/wpa_supplicant( 3631): COUNTRY Code Recived
,E/wpa_supplicant( 3631): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3631): baseband property is set to [msm]
,I/        ( 3560): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3560): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3560): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3560): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3560): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3560): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3560): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3560): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3560): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3560): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3560): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 3560): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3560): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3560): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3560): BTE_InitTraceLevels -- TRC_BTIF
,E/wpa_supplicant( 3631):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3631): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3631): card_info[i].card_state: 0x2
E/wpa_supplicant( 3631): card_info[i].error_code: 0x3
E/wpa_supplicant( 3631): SIM/USIM not ready
,E/wpa_supplicant( 3631): Error while reading SIM card status
E/wpa_supplicant( 3631): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3631): card_info[i].card_state: 0x2
E/wpa_supplicant( 3631): card_info[i].error_code: 0x3
E/wpa_supplicant( 3631): SIM/USIM not ready
,I/wpa_supplicant( 3631): eap_proxy: Card not ready
,D/WifiStateMachine( 1018): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: InitialState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): deferMessage: msg=131144
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): deferMessage: msg=131085
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131149
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1018): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147457
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): Supplicant connection established
,D/WifiStateMachine( 1018): setWifiState: enabled
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiConfigStore( 1018): Loading config and enabling all networks
,W/XTWiFiOS( 1267): Active network info is not available
,E/bt-btm  ( 3560): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f130049 
,E/bt-btm  ( 3560): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f130049 
,E/WifiConfigStore( 1018): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3631): COUNTRY Code Recived -COUNTRY PL
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
E/bt-btif ( 3560): Calling BTA_HhEnable
E/bt-btif ( 3560): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3560): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
D/WifiStateMachine( 1018): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartedState
,D/BluetoothAdapterProperties( 3560): Name is: XT1039
,I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3560): Scan Mode:21
I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 3560): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:8 len:6
,D/BluetoothAdapterProperties( 3560): Adding bonded device:B4:CE:F6:AB:A4:6A
,I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 3560): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
,D/WifiStateMachine( 1018): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1018): setDetailed state, old =IDLE and new state=DISCONNECTED
,I/bte_conf( 3560): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3560): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3560): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3560): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,E/bt_mct  ( 3560): hci lib postload completed
E/wpa_supplicant( 3631): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3631): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/BluetoothPanServiceJni( 3560): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 3560): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/WifiStateMachine( 1018): Attempting to reconnect to wifi network ..
D/BluetoothAdapterProperties( 3560): ScanMode =  21
D/BluetoothAdapterProperties( 3560): State =  11
D/BluetoothAdapterProperties( 3560): Setting state to 12
I/BluetoothAdapterState( 3560): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3560): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 3560): Entering On State
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1018): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan( 1018): onBluetoothStateChange on: true
,D/BluetoothHeadset( 1247): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=true
I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3560): Discoverable Timeout:120
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1018): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1018): onBluetoothStateChange: up=true
,D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1106941536)( 3560): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3560): getBondedDevices: length=1
,D/BluetoothMapService( 3560): onReceive
,D/BluetoothMapService( 3560): STATE_ON
D/BluetoothAdapterService(1106941536)( 3560): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3560): getBondedDevices: length=1
D/BluetoothManagerService( 1018): Message: 40
,D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/WifiP2pService( 1018): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring up p2p0
D/BluetoothMapService( 3560): Map Service startRfcommSocketListener
,D/WifiMonitor( 1018): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1018): P2pEnablingState
D/WifiP2pService( 1018): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2p socket connection successful
D/BluetoothAdapterService(1106941536)( 3560): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3560): getBondedDevices: length=1
D/WifiP2pService( 1018): P2pEnabledState
,D/WifiP2pService( 1018): sending p2p connection changed broadcast
D/WifiStateMachine( 1018): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1018): moveDeferredMessageAtFrontOfQueue; what=131144
D/BluetoothMapService( 3560): Map Service initSocket
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
I/qcom-bt-wlan-coex( 3660): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(1106941536)( 3560): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3560): getBondedDevices: length=1
W/BluetoothAdapter( 3560): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3560): SOCK FLAG = 1 ***********************
I/BluetoothAdapterProperties( 3560): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3560): Scan Mode:21
,D/BluetoothMapService( 3560): Accepting socket connection...
W/ContextImpl( 3597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiP2pService( 1018): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService( 1018): MCC mode enabled 0
D/WifiP2pService( 1018): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1018): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1018): InactiveState
D/WifiP2pService( 1018): InactiveState{ when=-7ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-7ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3631): COUNTRY Code Recived
E/wpa_supplicant( 3631): COUNTRY Code Recived
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44018910:true
,D/BluetoothPbapService( 3560): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3560): Handler(): got msg=1
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3560): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3560): SOCK FLAG = 1 ***********************
,D/LocalBluetoothProfileManager( 3597): Adding local A2DP profile
,D/BluetoothManagerService( 1018): Message: 30
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): handleMessage: X
,W/ContextImpl( 3597): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/WifiStateMachine( 1018): handleMessage: E msg.what=131152
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): set country code PL
E/wpa_supplicant( 3631): COUNTRY Code Recived
E/wpa_supplicant( 3631): COUNTRY Code Recived
D/LocalBluetoothProfileManager( 3597): Adding local HEADSET profile
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131162
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiP2pService( 1018): InactiveState{ when=0 what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): set frequency band 2
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothManagerService( 1018): Message: 30
D/WifiP2pService( 1018): InactiveState{ when=-3ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-3ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 3597): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
W/wpa_supplicant( 3631): wlan0: Failed to initiate AP scan
D/BluetoothManagerService( 1018): Message: 30
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,W/ContextImpl( 3597): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131167
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
E/SharedPreferencesImpl( 1018): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=143371
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/BluetoothManagerService( 1018): Message: 30
D/BluetoothAdapterService(1106941536)( 3560): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3560): getBondedDevices: length=1
,W/ContextImpl( 3597): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3597): Adding local MAP profile
D/BluetoothMap( 3597): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3597): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1018): Message: 30
,W/ContextImpl( 3597): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3597): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3597): finishStartingService: stopping service
,D/BluetoothAdapterService(1106941536)( 3560): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3560): getBondedDevices: length=1
,D/BluetoothA2dp( 3597): Proxy object connected
,D/A2dpProfile( 3597): Bluetooth service connected
,D/BluetoothHeadset( 3597): Proxy object connected
,D/HeadsetProfile( 3597): Bluetooth service connected
,D/BluetoothInputDevice( 3597): Proxy object connected
,D/HidProfile( 3597): Bluetooth service connected
,D/BluetoothPan( 3597): BluetoothPAN Proxy object connected
D/PanProfile( 3597): Bluetooth service connected
D/BluetoothMap( 3597): Proxy object connected
D/MapProfile( 3597): Bluetooth service connected
,D/BluetoothMap( 3597): getConnectedDevices()
,D/BluetoothPbap( 3597): Proxy object connected
,D/PbapServerProfile( 3597): Bluetooth service connected
,D/dalvikvm( 1018): GC_EXPLICIT freed 21903K, 65% free 17854K/49968K, paused 4ms+10ms, total 140ms
V/BluetoothFtpReceiver( 3560): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3560): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1326): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1326): Proximity feature is not enabled.
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothFtpService( 3560): Ftp Service onCreate
I/BluetoothFtpService( 3560): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3560): Starting FTP service
V/BluetoothFtpService( 3560): Ftp Service onStartCommand
V/BluetoothFtpService( 3560): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3560): Handler(): got msg=1
,W/BluetoothAdapter( 3560): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothFtpService( 3560): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3560): Ftp Service initSocket
,E/BluetoothServiceJni( 3560): SOCK FLAG = 0 ***********************
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/BtOppRfcommListener( 3560): Accept thread started.
,W/BluetoothAdapter( 3560): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3560): SOCK FLAG = 3 ***********************
V/BluetoothFtpService( 3560): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3560): Run Accept thread
,D/Checkin ( 2135): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2135): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/TCMD    (  444): NL - Read 1000 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
,D/TCMD    (  444): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  273): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): wifi_connect_to_supplicant, current pid is = 273
D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  273): wifi_close_sockets: Exit
,E/MDMCTBK (  273): Attach monitor thread
I/MDMCTBK (  273): createWifiMonitorThread: Started the wifi monitor thread -1210628824
,D/MDMCTBK (  273): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2135): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1018): InactiveState{ when=-2ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-2ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
W/wpa_supplicant( 3631): wlan0: Failed to initiate AP scan
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  273): Event received = Failed to initiate AP scan
D/WifiP2pService( 1018): P2pEnabledStateupdate channel list
,D/Checkin ( 2135): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/wpa_supplicant( 3631): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c0:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c2:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c2:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 06:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 06:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 0c:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 0c:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 fe:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 fe:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 64:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 64:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 fc:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 fc:
D/TCMD    (  444): NL - Read 56 bytes from update socket.
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  444): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3629): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3629): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
E/wpa_supplicant( 3631): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,I/wpa_supplicant( 3631): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3631): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  444): NL - Read 312 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/TCMD    (  444): Listening for incoming client connection request
D/TCMD    (  444): NL - Read 88 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/TCMD    (  444): Listening for incoming client connection request
D/TCMD    (  444): NL - Read 68 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/TCMD    (  444): Listening for incoming client connection request
D/TCMD    (  444): NL - Read 1000 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
,D/TCMD    (  444): Listening for incoming client connection request
I/wpa_supplicant( 3631): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/TCMD    (  444): NL - Read 80 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/TCMD    (  444): Listening for incoming client connection request
D/TCMD    (  444): NL - Read 80 bytes from update socket.
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/TCMD    (  444): Listening for incoming client connection request
D/TCMD    (  444): NL - Read 68 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
,D/TCMD    (  444): Listening for incoming client connection request
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3631): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3631): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/TCMD    (  444): NL - Read 1000 bytes from update socket.
D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/TCMD    (  444): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273):  STA Connected !!
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
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
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
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1210632928
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
,D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1018): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1018): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1018): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-50ms what=147462 obj=android.net.wifi.StateChangeResult@4202dbc0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-36ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@42480370 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42561918 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42561918 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  444): NL - Read 56 bytes from update socket.,
,D/TCMD    (  444): NL - message type is RTM_NEWLINK
D/TCMD    (  444): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 06
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 0c
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 fc
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 fc
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 10
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 10
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiP2pService( 1018): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@422fe090 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@422fe090 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@422fe090 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): handleMessage: X
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,D/TCMD    (  444): NL - Read 60 bytes from update socket.
D/TCMD    (  444): NL - ignore NL message, type = 20
,D/TCMD    (  444): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): DHCP successful
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1018): Calling ARP set with IP = 192.168.1.123
D/WifiStateMachine( 1018): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1018): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState enter
D/WifiStateMachine( 1018): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@420866f8
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): transitionTo: destState=ConnectedState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectedState
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: ConnectedState
I/ModemStatsDSDetect( 1290): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1290): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1290): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@420866f8
I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1290): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1290): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1290): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/        ( 1018): Unable to set rtc to 1448345067: Invalid argument
,D/        ( 1018): Setting time of day to sec=1448345067
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1535): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ActivityManager( 1018): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3741 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/PollingManager( 1535): now: 354510 ,futureTime: 16062777
,D/PollingManager( 1535): Polling alarm set to expire at: 16062777 Current Time: 354510
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1535): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1535): registerApp(): CCE
I/CCE     ( 1535): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1535): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1535): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1535): now: 354565 ,futureTime: 16062777
,D/PollingManager( 1535): Polling alarm set to expire at: 16062777 Current Time: 354565
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,E/ActivityThread( 1535): Failed to find provider info for com.motorola.blur.setupprovider
D/MMApiWebService( 1535): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/CCE     ( 1535): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1535): isRequestAllowed(): already have outstanding request ... ignoring request
D/CCE     ( 1535): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1535): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1535): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
D/OtaApp  ( 1535): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1535): [debug] > CusSM.onRadioUp
D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/OtaApp  ( 1535): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1535): generating token using payload instead of using session token
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1535): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/OtaApp  ( 1535): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1535): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1535): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/ActivityManager( 1018): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3767 uid=10056 gids={50056, 3003, 1028, 1015}
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1535): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1535): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1535): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1535): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1535): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 3741): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fa22a8, skipping init
I/openssl ( 3741): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3741): Crypto mode 0 already enabled
,I/VacuumService( 1326): Vacuum at: now=1448345068130 tag=VacuumService
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3796 uid=10030 gids={50030, 3003, 1028, 1015}
,I/dalvikvm( 1370): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1370): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1370): VFY: replacing opcode 0x6e at 0x0033
,I/ActivityManager( 1018): Killing 3359:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,V/MmsConfig( 3796): mnc/mcc: 
,V/MmsConfig( 3796): tag: bool value: enabledMMS - true
V/MmsConfig( 3796): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3796): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3796): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3796): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 3796): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3796): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3796): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3796): tag: int value: recipientLimit - 20
V/MmsConfig( 3796): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 3796): tag: int value: smsToMmsTextThreshold - 6
,E/Auth.Api.Credentials( 1370): [CredentialSyncAdapter] Unknown sync event.
,D/DelayedSyncController( 3767): Delaying sync.
V/MmsConfig( 3796): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3796): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 3796): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3796): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3796): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3796): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3796): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/GpsLocationProvider( 1018): NTP server returned: 1448345064844 (Tue Nov 24 07:04:24 CET 2015) reference: 351539 certainty: 21 system time offset: -3410
,E/LocSvc_ApiV02( 1018): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/dalvikvm( 1203): GC_EXPLICIT freed 2040K, 41% free 10298K/17224K, paused 2ms+6ms, total 42ms
,I/dalvikvm( 1203): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1203): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1203): VFY: replacing opcode 0x6e at 0x0033
,I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3822 uid=10041 gids={50041, 3003}
,E/DataBuffer( 1203): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422b6738)
I/ActivityManager( 1018): Killing 3056:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 3382:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1247): GC_EXPLICIT freed 1459K, 45% free 9519K/17224K, paused 3ms+6ms, total 73ms
,D/MobileConnectivityChangeReceiver( 3822): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3822): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3822): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3822): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3837 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3077:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1370): Checkin interval check for package: unspecified last checkin: 1448298937363 min interval config: 0 actual interval: 46131060
,I/CheckinService( 1370): Checking schedule, now: 1448345068427 next: 1448298967331
,I/CheckinService( 1370): active receiver: enabled
,I/CheckinService( 1370): Preparing to send checkin request
,I/EventLogService( 1370): Accumulating logs since 1448344089904
,V/WebViewChromiumFactoryProvider( 3837): Binding Chromium to main looper Looper (main, tid 1) {41f9f0f0}
,I/LibraryLoader( 3837): Expected native library version number "",actual native library version number ""
,I/chromium( 3837): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3837): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3837): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3837): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3837): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3837): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3837): Local Branch: 
I/Adreno-EGL( 3837): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3837): Local Patches: NONE
I/Adreno-EGL( 3837): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1370): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1018): New client listening to asynchronous messages
,E/ActivityThread( 1370): Failed to find provider info for com.google.android.wearable.settings
W/chromium( 3837): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/dalvikvm( 1370): GC_CONCURRENT freed 1637K, 33% free 11690K/17224K, paused 4ms+9ms, total 50ms
D/DelayedSyncController( 3767): Delaying sync.
,W/GAV2    ( 3837): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3837): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1018): GC_EXPLICIT freed 1724K, 65% free 17864K/49968K, paused 4ms+11ms, total 101ms
,I/dalvikvm( 1018): Jit: resizing JitTable from 8192 to 16384
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3837): Starting up...
,I/ImageResourceManager( 3111): ImageResourceManager: uninitalized
,I/iu.Environment( 3111): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3111): SYNC; picasa accounts
I/ActivityManager( 1018): Killing 3410:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3111): num queued entries: 0
,I/iu.UploadsManager( 3111): num updated entries: 0
,I/iu.SyncManager( 3111): NEXT; no task
,I/iu.SyncManager( 1370): SYNC; picasa accounts
,D/MMApiWSBase( 1535): doRequest(): v1/ns/list/messages resp length: 1465
,D/NetworkLogImpl( 1370): Loaded NetworkSpeedPredictor
,D/CCE     ( 1535): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
D/CCE     ( 1535): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/iu.Environment( 1370): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1370): num queued entries: 0
,I/iu.UploadsManager( 1370): num updated entries: 0
,I/iu.SyncManager( 1370): NEXT; no task
,I/openssl ( 3741): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3741): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3822): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3822): onReceive CONNECTIVITY_CHANGE networkType=1
,D/Checkin ( 1535): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1535): handleGetNotificationsResponse(): got 0; more=false
,D/MMApiProvisionService( 1535): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"13382","deviceId":"1135300315450105856"}
,I/iu.Environment( 3111): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/MMApiProvisionService( 1535): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1535): doRequest(): /v1/dp/devices.json resp length: 137
,D/MMApiProvisionService( 1535): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1535): handleResponse(): Session Expiration alarm set to expire at: Tue Nov 24 10:47:31 CET 2015
,D/MMApiProvisionService( 1535): _setMMApiCredInfo: storing credential info 
,D/dalvikvm( 3111): GC_CONCURRENT freed 624K, 5% free 16454K/17224K, paused 3ms+7ms, total 27ms
,D/DEBUG   ( 1535): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1535): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=1
,E/MMApiProvisionService( 1535): handleResponse(): no settings sent by the server:
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/EmailService.MarketingOptInSetter( 1535): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3894 uid=10007 gids={50007, 3003}
D/MMApiWebService( 1535): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/ExtensionsFactory( 3894): No custom extensions.
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3911 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 3139:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3923 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3597:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1018): Client connection lost with reason: 4
,V/AlarmClock( 3911): AlarmInitReceiver android.intent.action.TIME_SET
,I/AlarmClock( 3911): Displaying next alarm time: ''
,I/CalendarProvider2( 3923): Created com.android.providers.calendar.CalendarAlarmManager@41fbae70(com.android.providers.calendar.CalendarProvider2@41fb2a28)
,V/AlarmClock( 3911): AlarmInitReceiver finished
,I/ActivityManager( 1018): Killing 3741:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3941 uid=10098 gids={50098}
I/GCM     ( 1326): GCM config loaded
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 24ms
,D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,D/dalvikvm( 3941): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41fa6f30, skipping init
D/TimeService( 3941): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448345069386
D/        ( 3941): TimeServiceNative: User Time to be set is 1448345069386
D/QC-time-services( 3941): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3941): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3941): Lib:time_genoff_operation: pargs->ts_val = 1448345069386
,D/QC-time-services(  400): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3941): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  400): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448345069386
,D/QC-time-services(  400): Daemon:genoff_opr: Base = 2, val = 1448345069386, operation = 0
D/QC-time-services(  400): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/24/115 5:58:38
D/QC-time-services(  400): Daemon:Value read from RTC seconds = 1448344718000
D/QC-time-services(  400): Daemon:new time 1448345069386 
D/QC-time-services(  400): Daemon: delta 351386 genoff 351386 
D/QC-time-services(  400): Daemon:genoff_persistent_update: Writing genoff = 351386 to memory
D/QC-time-services(  400): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  400): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  400): Updating the TOD offset
D/QC-time-services(  400): Daemon:genoff_persistent_update: Writing genoff = 351386 to memory
D/QC-time-services(  400): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  400): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  400): Daemon:Update to modem bit set
D/QC-time-services(  400): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  400): Daemon: Base = 2, Value being sent to MODEM = 18446743757745103002
,E/QC-time-services( 3941): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  400): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  400): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1370): Checkin interval check for package: unspecified last checkin: 1448298937363 min interval config: 0 actual interval: 46132060
,D/UdcCache:FPQuery( 1370): Bootstrapping UDC settings cache for all accounts
,D/dalvikvm( 1326): GC_CONCURRENT freed 1947K, 39% free 10630K/17224K, paused 3ms+3ms, total 34ms
,D/DEBUG   ( 1535): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1535): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1535): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1535): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1535): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1535
,I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1535): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1535
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
,I/LaunchCheckinHandler( 1018): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,112
D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/DEBUG   ( 1535): Received intent : com.motorola.ccc.notification.action.NOTIFY
,D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{41f920e0 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
I/SundryService( 1535): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1535): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1535): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=0
D/DEBUG   ( 1535): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
D/GetNotificationsWS( 1535): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1535): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1535): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 1535): onServiceConnected()
,D/GetNotificationsWS( 1535): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1535): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1535): Received shoulder tap
,D/dalvikvm( 1535): GC_CONCURRENT freed 2416K, 38% free 10772K/17224K, paused 2ms+4ms, total 42ms
,D/WaitableIntentService( 1535): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1535): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1535): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3966 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,I/MMApiWSBase( 1535): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,W/dalvikvm( 3966): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3966): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 3966): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 3966): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3966): VFY: replacing opcode 0x6e at 0x00ca
,I/MultiDex( 3966): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3966): install
,I/MultiDex( 3966): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,D/GetConfigurationSnapshotOperation( 1326): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/MultiDex( 3966): loading existing secondary dex files
,I/MultiDex( 3966): load found 3 secondary dex files
,I/MultiDex( 3966): install done
,D/dalvikvm( 3966): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 3966): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3966): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 3966): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3966): VFY: unable to resolve instance field 46
,D/dalvikvm( 3966): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 3966): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3966): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3966): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 3966): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3966): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 3966): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f9d098
,D/dalvikvm( 3966): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f9d098
D/dalvikvm( 3966): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f9d098, skipping init
,I/PhenotypeFlagCommitter( 1326): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/dalvikvm( 3966): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f9d098
,D/dalvikvm( 3966): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f9d098
,V/JNIHelp ( 3966): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/GoogleURLConnFactory( 1326): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 3966): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f9d098
,D/dalvikvm( 3966): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41f9d098
D/dalvikvm( 3966): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f9d098
,D/dalvikvm( 3966): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f9d098
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1290): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1290): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1290): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1290): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/GetCommittedConfigurationOperation( 1326): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ProviderInstaller( 3966): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1203): callingUid 10022, callindPid: 1203
,E/MDM     ( 1203): [76] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/dalvikvm( 3966): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 3966): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 3966): VFY: replacing opcode 0x6e at 0x000d
,D/GCM     ( 1326): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1326): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1326): Proximity feature is not enabled.
I/dalvikvm( 3966): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 3966): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3966): VFY: replacing opcode 0x6e at 0x0220
,D/LocationInitializer( 1370): Restart initialization of location
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1370): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 3966): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3966): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 3966): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 3966): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 3966): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3966): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 3966): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3966): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 3966): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 3966): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 3966): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1326): location=null
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/QSEECOMAPI: (  278): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/QSEECOMAPI: (  278): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  278): App is not loaded in QSEE
,I/dalvikvm( 3966): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 3966): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3966): VFY: replacing opcode 0x6e at 0x0033
,W/dalvikvm( 3966): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3966): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3966): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/QSEECOMAPI: (  278): Loaded image: APP id = 3
I/dalvikvm( 3966): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 3966): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 3966): VFY: replacing opcode 0x6e at 0x00bb
,D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5211000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5211000
,I/GoogleURLConnFactory( 3966): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
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
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=155397047
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/MMApiWSBase( 1535): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1535): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1535): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/CalendarProvider2( 3923): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3923): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3894): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3894): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 1326): GC_CONCURRENT freed 1602K, 37% free 10968K/17224K, paused 4ms+25ms, total 68ms
,D/NativeLibraryUtils( 3966): Install completed successfully. count=13 extracted=0
,D/Checkin ( 1535): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1535): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1535): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1535): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1535): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1535): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1535): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1535): unbindWebServices(): un-registering our AIDL callback...
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/GetCommittedConfigurationOperation( 1326): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1326):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1326): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1326): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 3966): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42338fc8
D/dalvikvm( 3966): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42338fc8
,D/dalvikvm( 3966): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42338fc8, skipping init
,D/GetCommittedConfigurationOperation( 1326): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 3966): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4005): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 3966): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3966): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 99ms
,I/Adreno-EGL( 3966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3966): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3966): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3966): Local Branch: 
I/Adreno-EGL( 3966): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3966): Local Patches: NONE
I/Adreno-EGL( 3966): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3966): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3966): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3966): Local Branch: 
I/Adreno-EGL( 3966): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3966): Local Patches: NONE
I/Adreno-EGL( 3966): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 3966): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 3966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3966): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3966): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3966): Local Branch: 
I/Adreno-EGL( 3966): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3966): Local Patches: NONE
I/Adreno-EGL( 3966): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3966): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3966): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3966): Local Branch: 
I/Adreno-EGL( 3966): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3966): Local Patches: NONE
I/Adreno-EGL( 3966): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=3440653687
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/CheckinRequestBuilder( 1370): Classify the device as Phone.
,I/CheckinTask( 1370): Sending checkin request (11808 bytes)
,I/CheckinRequestBuilder( 1370): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1370): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1018): GC_EXPLICIT freed 877K, 65% free 17808K/49968K, paused 4ms+10ms, total 89ms
,I/CheckinRequestBuilder( 1370): Classify the device as Phone.
,I/CheckinTask( 1370): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1370): Checking schedule, now: 1448345073332 next: 1448938143324
,I/CheckinService( 1370): active receiver: disabled
,D/CheckinService( 1370): Recording last checkin time for package unspecified as 1448345073357
,D/dalvikvm( 1370): GC_CONCURRENT freed 1989K, 33% free 11682K/17224K, paused 4ms+4ms, total 50ms
,D/GCM     ( 1326): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 3837): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 3894): no sender configured
,D/AlertService( 3894): Beginning updateAlertNotification
,D/AlertService( 3894): No fired or scheduled alerts
,D/AlertService( 3894): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3894): No events found starting within 1 week.
I/ActivityManager( 1018): Killing 3796:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 3822:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1018): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1018): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1018): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1018): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1018): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4033 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/Launcher( 1302): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/Launcher( 1302): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1203): DISABLE
,I/GCoreNlp( 1203): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4033): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4033): MmsConfig.loadMmsSettings
,I/Babel   ( 4033): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4033): MmsConfig.loadFromDatabase
,E/Babel   ( 4033): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4033): MmsConfig.loadFromResources
,E/Babel   ( 4033): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4033): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4033): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4064 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1018): Killing 3767:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 3837:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4085 uid=10033 gids={50033, 3003, 1028, 1015}
,I/InternalIcingCorporaPro( 2181): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1370): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4102 uid=10038 gids={50038, 3003, 1028, 1015}
I/PackageBroadcastService( 1370): Null package name or gms related package.  Ignoreing.
,D/dalvikvm( 3111): GC_FOR_ALLOC freed 43K, 5% free 16419K/17224K, paused 38ms, total 38ms
,I/dalvikvm-heap( 3111): Grow heap (frag case) to 19.803MB for 1821008-byte allocation
,I/Icing   ( 1370): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 3111): GC_FOR_ALLOC freed 5K, 5% free 18196K/19004K, paused 11ms, total 11ms
,I/ActivityManager( 1018): Killing 3923:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4064): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4102): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4102): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4102): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4102): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4102): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4102): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4102): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4102): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4102): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4102): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x0032
,I/InternalIcingCorporaPro( 2181): UpdateCorporaTask done [took 296 ms] updated apps [took 296 ms] 
,W/Settings( 4102): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4102): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4102): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4102): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4102): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4102): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4102): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4138 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4102): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4102): Skipping gmscore version check
,D/Finsky  ( 4102): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4102): [1] Libraries$2.run: Finished loading 1 libraries.
,I/dalvikvm( 4102): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4102): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4102): VFY: replacing opcode 0x6e at 0x0017
I/ActivityManager( 1018): Killing 3941:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 4138): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fa4318, skipping init
I/openssl ( 4138): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4138): Crypto mode 0 already enabled
,D/Finsky  ( 4102): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4102): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1018): Killing 3911:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): Attempting to connect to the test coordinator server
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): Test app app.js loaded
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":0}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): LogCallback not set !!!!
I/jxcore-log( 3505): 
,I/Choreographer( 3505): Skipped 1273 frames!  The application may be doing too much work on its main thread.
,W/IInputConnectionWrapper( 3505): showStatusIcon on inactive InputConnection
,I/chromium( 3505): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): DBG, CoordinatorConnector connect called
I/jxcore-log( 3505): 
,V/AlarmManager( 1018): sending alarm Alarm{42832368 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{42811e18 type 3 android}
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43c026e8 type 3 android}
,I/ClearcutLoggerApiImpl( 1326): disconnect managed GoogleApiClient
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
,V/AlarmManager( 1018): sending alarm Alarm{43c75f30 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
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
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9
,V/AlarmManager( 1018): sending alarm Alarm{440b81d8 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{420d2ca8 type 3 android}
,I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
I/jxcore-log( 3505): got start_tests event with data : {"data":{"devices":{"ios":4,"android":19}}}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":0}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"test connectionTable table building and cleanup","id":1}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1448345354371},"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":1}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: undefined : test connectionTable table building and cleanup", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : Cleanup was called, this table is no longer live.", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":2}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":3}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":3}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":4}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: undefined : test connectionTable emitting events for peerIds", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":5}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":6}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 6 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":6}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"start with bad friendly names","id":7}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":7}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 7 isOK: undefined : start with bad friendly names", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 8 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":8}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":9}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 9 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":9}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 10 isOK: undefined : make sure startIdentityExchange sets things up properly", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: EblgisyueLmRjUpx2cDLdA==;Matt
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":50888,"expected":50888,"test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"EblgisyueLmRjUpx2cDLdA==;Matt","expected":"EblgisyueLmRjUpx2cDLdA==;Matt","test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":10}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 11 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3505): {"type":"end","test":11}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":12}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 12 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
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
,I/jxcore-log( 3505): {"type":"end","test":12}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":13}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: wGrhwZnBxUJEGerfYa7FGQ==;Toby
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":37735,"expected":37735,"test":13,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"wGrhwZnBxUJEGerfYa7FGQ==;Toby","expected":"wGrhwZnBxUJEGerfYa7FGQ==;Toby","test":13,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 13 isOK: undefined : make sure we get an error if we call start and then immediately call stop", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 14 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":14}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":15}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 15 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":15}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"Make sure stop is clean from start","id":16}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: E5MJZ2aTZCQSh8nmFKGcsg==;Luke
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":38853,"expected":38853,"test":16,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"E5MJZ2aTZCQSh8nmFKGcsg==;Luke","expected":"E5MJZ2aTZCQSh8nmFKGcsg==;Luke","test":16,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":16}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 16 isOK: undefined : Make sure stop is clean from start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : Should not have gotten error on startIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : Should not have gotten error on stopIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : State should be Stopped", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 17 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1018): sending alarm Alarm{43d20258 type 3 android}
,I/jxcore-log( 3505): {"type":"end","test":17}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":18}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 18 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":18}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: PtVdTJrMHAqCuu3cW8Ys6w==;Jukka
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":52564,"expected":52564,"test":19,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"PtVdTJrMHAqCuu3cW8Ys6w==;Jukka","expected":"PtVdTJrMHAqCuu3cW8Ys6w==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":19}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 19 isOK: undefined : Make sure stop is clean from stop execute identity exchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 20 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":20}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":21}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 21 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":21}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Dc6QX96Qc/+sicfsQJLXOg==;Doug
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":52794,"expected":52794,"test":22,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"Dc6QX96Qc/+sicfsQJLXOg==;Doug","expected":"Dc6QX96Qc/+sicfsQJLXOg==;Doug","test":22,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":22}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 22 isOK: undefined : make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 23 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3505): {"type":"end","test":23}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":24}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 24 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":24}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: h1J/U10mtuF/2bi/3BWqDA==;David
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":56067,"expected":56067,"test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"h1J/U10mtuF/2bi/3BWqDA==;David","expected":"h1J/U10mtuF/2bi/3BWqDA==;David","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: h1J/U10mtuF/2bi/3BWqDA==;David
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":56067,"expected":56067,"test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"h1J/U10mtuF/2bi/3BWqDA==;David","expected":"h1J/U10mtuF/2bi/3BWqDA==;David","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":25}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 25 isOK: undefined : illegal method combinations", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 26 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":26}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":27}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 27 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
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
,I/jxcore-log( 3505): {"type":"end","test":27}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 28 isOK: undefined : do an identity exchange and get code multiple times to make sure we do not hork state", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":500288,"expected":500288,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":347136,"expected":347136,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":691776,"expected":691776,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":142848,"expected":142848,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
I/jxcore-log( 3505): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":427200,"expected":427200,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 75 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 76 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 77 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 78 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 79 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 80 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 81 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 82 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 83 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":355968,"expected":355968,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 84 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 85 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 86 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 87 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 88 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 89 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 90 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 91 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 92 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 93 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":246912,"expected":246912,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 94 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 95 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 96 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 97 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 98 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 99 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 100 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 101 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 102 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 103 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 104 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 105 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 106 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 107 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 108 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 109 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 110 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 111 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 112 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 113 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":343680,"expected":343680,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 114 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 115 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 116 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 117 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 118 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 119 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 120 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 121 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 122 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 123 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":839424,"expected":839424,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 124 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 125 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 126 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 127 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 128 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 129 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 130 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 131 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 132 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 133 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 134 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 135 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 136 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 137 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 138 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":705856,"expected":705856,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: Pis72eDYXMKZ4ia8Om6nJw==;John
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":41491,"expected":41491,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"Pis72eDYXMKZ4ia8Om6nJw==;John","expected":"Pis72eDYXMKZ4ia8Om6nJw==;John","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO identityExchange We will advertise the following device name as we start: yvuDY0epQAI1/ecNreEzPA==;Srikanth
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":41318,"expected":41318,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","expected":"yvuDY0epQAI1/ecNreEzPA==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/cb request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 139 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 140 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 141 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 142 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 143 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 144 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 145 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 146 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): INFO smallerHash Making /identity/rnmine request to pkOther value yvuDY0epQAI1/ecNreEzPA==
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 147 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":542784,"expected":542784,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":28}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 148 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 149 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 150 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 151 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 152 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 153 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 154 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 155 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 156 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 157 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 158 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 159 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 160 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 161 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 162 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 163 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 164 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 29 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":29}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":30}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 30 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":30}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":31}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 31 isOK: undefined : test compareEqualSizeBuffers", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 32 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":32}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":33}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 33 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":33}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":34}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 34 isOK: undefined : Make sure we return 404 before hitting start", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 35 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"end","test":35}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"setup","id":36}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 36 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1018): sending alarm Alarm{42825b98 type 3 android}
,I/jxcore-log( 3505): {"type":"end","test":36}
I/jxcore-log( 3505): 
,E/jxcore-log( 3505): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 3505): 
,E/jxcore-log( 3505): Trace: 
E/jxcore-log( 3505):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 3505):     at addListener@events.js:140:7
E/jxcore-log( 3505):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 3505):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 3505):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 3505):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 3505):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 3505):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,E/jxcore-log( 3505): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 3505): 
,E/jxcore-log( 3505): Trace: 
E/jxcore-log( 3505):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 3505):     at addListener@events.js:140:7
E/jxcore-log( 3505):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 3505):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 3505):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 3505):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 3505):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 3505):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3505): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"end","test":37}
I/jxcore-log( 3505): 
,I/jxcore-log( 3505): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 3505): 
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 37 isOK: undefined : Random path after start, need 404", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3505): [INFO:CONSOLE(63)] "logCallback 38 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43bb8a00 type 3 android}
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
,I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
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
,V/AlarmManager( 1018): sending alarm Alarm{4303b660 type 3 android}
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
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42ead280 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{43d96c80 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42803098 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1018): sending alarm Alarm{42802df0 type 1 com.android.deskclock}
,D/ConnectivityService( 1018): Done.
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4326 uid=10015 gids={50015, 1028}
,D/ConnectivityService( 1018): Setting timer for 720seconds
,I/ActivityManager( 1018): Killing 3894:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,V/AlarmManager( 1018): sending alarm Alarm{42815800 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{43cf23a0 type 3 android}
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 1018): GC_CONCURRENT freed 1926K, 65% free 17964K/49968K, paused 24ms+9ms, total 114ms
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
,V/AlarmManager( 1018): sending alarm Alarm{42c88ef8 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{44715698 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{44703920 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{440b8a70 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4246aea0 type 2 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{422cc118 type 0 com.google.android.gms}
,D/UdcCache:FPQuery( 1370): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1370): Aggregate from 1448345068544 (log), 1448344089904 (data)
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1290): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1290): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1290): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1018): sending alarm Alarm{4250f300 type 3 android}
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{425c2f70 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{42143a58 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{43030808 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{424a84d0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{427c9638 type 3 android}
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
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = ,
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{422375d8 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4215c128 type 3 android}
,I/ProcessStatsService( 1018): Prepared write state in 26ms
,I/ProcessStatsService( 1018): Prepared write state in 26ms
,I/ProcessStatsService( 1018): Prepared write state in 16ms
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2015-11-23-14-46-51.bin
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
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42913060 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{424b2ec0 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1018): sending alarm Alarm{424713e0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4246deb8 type 3 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{42469b18 type 3 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{42466c28 type 1 com.android.deskclock}
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PerfProfileCollectorService( 1370): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1370): removeStateFiles() called
,D/PerfProfileCollectorService( 1370): User is not opt-in to Usage & Diagnostics.
,D/dalvikvm( 1326): GC_CONCURRENT freed 2004K, 37% free 10921K/17224K, paused 6ms+5ms, total 42ms
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
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43c9d2c8 type 3 android}
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
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43cd5758 type 3 android}
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43bd7630 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{421dcf48 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4471): 
D/AndroidRuntime( 4471): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4471): CheckJNI is OFF
D/dalvikvm( 4471): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4471): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4471): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4471): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4471): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4471): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4471): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4471): failed to load memtrack module: -2
D/AndroidRuntime( 4471): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10407 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 3505:com.test.thalitest/u0a407 (adj 9): stop com.test.thalitest
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{42e87340 u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings( 1018): Skipping PackageSetting{4225d490 com.example.hello/10406} due to missing metadata
I/WindowState( 1018): WIN DEATH: Window{42e5d1b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1018): Client connection lost with reason: 4
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10407 user=0: pkg removed
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1203): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
D/dalvikvm( 2135): GC_EXPLICIT freed 6307K, 44% free 9741K/17224K, paused 2ms+10ms, total 57ms
D/dalvikvm( 1302): GC_EXPLICIT freed 2892K, 33% free 11593K/17224K, paused 15ms+6ms, total 89ms
D/dalvikvm( 2181): GC_EXPLICIT freed 3300K, 42% free 10063K/17224K, paused 2ms+5ms, total 104ms
D/dalvikvm( 1018): GC_EXPLICIT freed 1740K, 65% free 17978K/49968K, paused 4ms+11ms, total 119ms
I/Launcher( 1302): Deferring update until onResume
I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
D/VoicemailCleanupService( 4064): Cleaning up data for package: com.test.thalitest
I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448346866
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/Launcher( 1302): Deferring update until onResume
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2181): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4501 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10407 #1
I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448346866
I/InternalIcingCorporaPro( 2181): UpdateCorporaTask done [took 95 ms] updated apps [took 95 ms] 
D/dalvikvm( 1018): GC_EXPLICIT freed 654K, 65% free 17950K/49968K, paused 8ms+14ms, total 185ms
D/AndroidRuntime( 4471): Shutting down VM
D/dalvikvm( 4471): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4501): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4526 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1018): Killing 3966:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/GAV2    ( 4501): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4526): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1370): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1370): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1370): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1370): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1370): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1326): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDatabase( 1370): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1370): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1370): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1370): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1370): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1370): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1370): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/AndroidRuntime( 1326): Shutting down VM
W/dalvikvm( 1326): threadid=1: thread exiting with uncaught exception (group=0x416cdd40)
E/SQLiteOpenHelper( 1370): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1370): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1370): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1370): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1370): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1370): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1370): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1370): Opened phenotype.db in read-only mode
E/AndroidRuntime( 1326): FATAL EXCEPTION: main
E/AndroidRuntime( 1326): Process: com.google.process.gapps, PID: 1326
E/AndroidRuntime( 1326): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1326): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1326): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1326): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1326): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1326): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1326): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1326): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1326): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1326): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1326): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1326): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1326): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1326): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1326): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1326): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1326): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1326): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1326): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1326): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1326): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1326): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1326): 	... 10 more
D/ChimeraCfgMgr( 1370): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1370): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1370): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1370): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1370): (3850) statement aborts at 26: [DELETE FROM events WHERE app_id=?] disk I/O error
E/GMPM-SVC( 1370): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
I/Process ( 1326): Sending signal. PID: 1326 SIG: 9
E/SharedPreferencesImpl( 1370): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SQLiteDatabase( 4526): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4526): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4526): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4526): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4526): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4526): threadid=10: thread exiting with uncaught exception (group=0x416cdd40)
E/ClearPendingStateOp( 1370): Runtime exception while performing operation
E/ClearPendingStateOp( 1370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1370): 	at com.google.android.gms.common.i.a.b(SourceFile:283)
E/ClearPendingStateOp( 1370): 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1370): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 1370): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/ClearPendingStateOp( 1370): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1370): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1370): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 1370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1370): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1370): 	at java.lang.Thread.run(Thread.java:841)
I/PeopleContactsSync( 1370): CP2 sync disabled
E/DropBoxManagerService( 1018): Can't write: system_app_crash
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 5 more
I/Icing   ( 1370): doRemovePackageData com.test.thalitest
E/DriveAsyncService( 1370): disk I/O error (code 3850)
E/DriveAsyncService( 1370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1370): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1370): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1370): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1370): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1370): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1370): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1370): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1370): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1370): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1370): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1370): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1370): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1370): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 1370): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1370): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1370): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1370): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1370): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1370): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1370): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1370): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1370): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1370): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1370): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1370): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteOpenHelper( 1370): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1370): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1370): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1370): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1370): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1370): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1370): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1370): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1370): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1370): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1370): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1370): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4526): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4526): Process: com.android.keychain, PID: 4526
E/AndroidRuntime( 4526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4526): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4526): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4526): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4526): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1370): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1370): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1370): 	at com.google.android.gms.common.i.a.b(SourceFile:283)
F/ClearPendingStateOp( 1370): 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1370): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 1370): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
F/ClearPendingStateOp( 1370): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1370): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1370): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 1370): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1370): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1370): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1370): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 1370): threadid=50: thread exiting with uncaught exception (group=0x416cdd40)
W/SQLiteOpenHelper( 1370): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1370): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1370): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1370): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1370): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1370): threadid=47: thread exiting with uncaught exception (group=0x416cdd40)
E/DropBoxManagerService( 1018): Can't write: system_app_wtf
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 5 more
E/DropBoxManagerService( 1018): Can't write: system_app_crash
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1018): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1018): 	... 5 more
I/Process ( 4526): Sending signal. PID: 4526 SIG: 9
W/FileUtils( 1370): Failed to chmod(/data/data/com.google.android.gms/files): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/GAv4-SVC( 1370): Error creating clientId file: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/gaClientId: open failed: EROFS (Read-only file system)
I/ActivityManager( 1018): Process com.google.process.gapps (pid 1326) has died.
D/WifiService( 1018): Client connection lost with reason: 4
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService in 1000ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService$LightweightWorkerService in 11000ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 20999ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
E/SharedPreferencesImpl( 1370): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/RocketImpressions( 1370): ClearcutLogger connection suspended: 1
I/ActivityManager( 1018): Process com.android.keychain (pid 4526) has died.

```
