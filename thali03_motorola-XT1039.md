#### Test 506502789252e15_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
V/GLSActivity( 2025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3549): 
D/AndroidRuntime( 3549): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3549): CheckJNI is OFF
D/dalvikvm( 3549): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3549): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3549): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3549): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3549): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3549): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3549): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3549): failed to load memtrack module: -2
D/AndroidRuntime( 3549): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3549
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3565 uid=10455 gids={50455, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3549): Shutting down VM
D/dalvikvm( 3549): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
D/dalvikvm(  279): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 20ms
V/WebViewChromiumFactoryProvider( 3565): Binding Chromium to main looper Looper (main, tid 1) {427c5ad8}
I/LibraryLoader( 3565): Expected native library version number "",actual native library version number ""
I/chromium( 3565): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3565): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44617e10:true
D/BluetoothAdapter( 3565): 1115529448: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3565): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3565): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3565): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3565): Local Branch: 
I/Adreno-EGL( 3565): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3565): Local Patches: NONE
I/Adreno-EGL( 3565): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3565): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3565): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3565): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3565): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3565): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3565): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3565): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3565): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3565): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3565): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3565): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3565): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3565): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3565): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3565): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3565): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3565): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3565): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3565): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3565): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3565): Enabling debug mode 0
,W/AwContents( 3565): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3565): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,418
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +385ms (total +418ms)
,D/JsMessageQueue( 3565): Set native->JS mode to OnlineEventsBridgeMode
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 3565): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427c9f88
,D/dalvikvm( 3565): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427c9f88
D/jxcore_app_log( 3565): JniHelper::setJavaVM(0x41edef78), pthread_self() = 1615063032
,D/JX-Cordova( 3565): jxcore cordova android initializing
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/dalvikvm( 3565): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3565): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3565): VFY: replacing opcode 0x6e at 0x0045
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 3565): GC_CONCURRENT freed 2794K, 17% free 14395K/17224K, paused 2ms+2ms, total 62ms
,D/dalvikvm( 3565): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 129K, 17% free 14390K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 16.146MB for 63974-byte allocation
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 154K, 17% free 14387K/17288K, paused 24ms, total 24ms
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 183K, 17% free 14421K/17288K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 16.252MB for 143930-byte allocation
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 255K, 18% free 14468K/17432K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 16.368MB for 215890-byte allocation
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 368K, 18% free 14541K/17644K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 567K, 19% free 14662K/17964K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 16.815MB for 485740-byte allocation
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 864K, 20% free 14837K/18440K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 17.217MB for 728606-byte allocation
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 1281K, 22% free 15093K/19152K, paused 27ms, total 27ms
,D/dalvikvm( 3565): GC_CONCURRENT freed 1677K, 20% free 15465K/19152K, paused 1ms+3ms, total 41ms
,D/dalvikvm( 3565): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 369K, 20% free 15420K/19152K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 18.655MB for 1639352-byte allocation
,D/dalvikvm( 3565): GC_CONCURRENT freed 1698K, 23% free 16012K/20756K, paused 1ms+5ms, total 38ms
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 1355K, 23% free 16066K/20756K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 20.067MB for 2459024-byte allocation
,D/dalvikvm( 3565): GC_CONCURRENT freed 227K, 21% free 18382K/23160K, paused 4ms+4ms, total 40ms
,D/dalvikvm( 3565): GC_CONCURRENT freed 4376K, 27% free 17046K/23160K, paused 1ms+7ms, total 50ms
,D/dalvikvm( 3565): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/dalvikvm-heap( 3565): Grow heap (frag case) to 22.197MB for 3688532-byte allocation
,D/dalvikvm( 3565): GC_CONCURRENT freed 2912K, 33% free 18088K/26764K, paused 1ms+8ms, total 58ms
,D/dalvikvm( 3565): GC_FOR_ALLOC freed 658K, 33% free 17973K/26764K, paused 27ms, total 27ms
,W/jxcore-log( 3565): Initializing JXcore engine
,W/jxcore-log( 3565): JXcore engine is ready
,D/dalvikvm( 3565): GC_CONCURRENT freed 355K, 24% free 20596K/26764K, paused 2ms+2ms, total 36ms
,D/dalvikvm( 3565): WAIT_FOR_CONCURRENT_GC blocked 31ms
,W/jxcore-log( 3565): Starting JXcore engine
,W/jxcore-log( 3565): Platform android
W/jxcore-log( 3565): 
,W/jxcore-log( 3565): Process ARCH arm
W/jxcore-log( 3565): 
,I/jxcore-log( 3565): JXcore Cordova bridge is ready!
I/jxcore-log( 3565): 
,W/jxcore-log( 3565): JXcore engine is started
,I/chromium( 3565): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3565): Toggling radios to true
I/jxcore-log( 3565): 
D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1020): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1020): Message: 1
D/BluetoothManagerService( 1020): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1272): Active network info is not available
,D/WifiService( 1020): setWifiEnabled: true pid=3565, uid=10455
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager( 1020): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3615 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,D/WifiService( 1020): New client listening to asynchronous messages
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiStateMachine( 1020): setting operational mode to 1
D/WifiStateMachine( 1020): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1020): processMsg: InitialState
,I/jxcore-log( 3565): Radios toggled
I/jxcore-log( 3565): 
,W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/XTWiFiOS( 1272): Active network info is not available
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/AdapterServiceConfig( 3615): Adding HeadsetService
D/AdapterServiceConfig( 3615): Adding A2dpService
D/AdapterServiceConfig( 3615): Adding HidService
D/AdapterServiceConfig( 3615): Adding HealthService
D/AdapterServiceConfig( 3615): Adding PanService
D/AdapterServiceConfig( 3615): Adding GattService
,D/AdapterServiceConfig( 3615): Adding BluetoothMapService
,D/BluetoothAdapterService( 3615): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1020): Message: 20
,D/BluetoothAdapterState( 3615): make
,D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43e13280:true
,I/BluetoothAdapterState( 3615): Entering OffState
,I/bluedroid( 3615): init
,I/bte_conf( 3615): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3615): get_profile_interface socket
,D/BluetoothManagerService( 1020): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1020): Message: 40
,D/BluetoothManagerService( 1020): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3615): config_hci_snoop_log
D/BluetoothManagerService( 1020): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceUp() to 7 receivers.
,I/GKI_LINUX( 3615): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3615): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothAdapterState( 3615): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3615): Name is: XT1039
,D/BluetoothManagerService( 1020): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1020): Stored Bluetooth name: XT1039
,D/BluetoothAdapterProperties( 3615): Setting state to 11
I/BluetoothAdapterState( 3615): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3615): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1020): Message: 60
,D/BluetoothManagerService( 1020): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1020): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3615): make
,I/BluetoothBondStateMachine( 3615): StableState(): Entering Off State
,I/ActivityManager( 1020): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3652 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/BluetoothHeadset( 1020): Proxy object connected
,D/BluetoothHeadset( 1242): Proxy object connected
,D/BluetoothHeadset( 1242): Proxy object connected
D/BluetoothHeadset( 1242): Proxy object connected
,D/HeadsetService( 3615): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3615): classInitNative: succeeds
D/HeadsetStateMachine( 3615): Version 1.6
,D/HeadsetStateMachine( 3615): make
,I/BluetoothAdapterState( 3615): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3615): get_profile_interface handsfree
,D/BluetoothA2dp( 1020): Proxy object connected
,D/A2dpService( 3615): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3615): classInitNative: succeeds
V/Avrcp   ( 3615): make
,I/bluedroid( 3615): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3615): classInitNative: succeeds
,D/A2dpStateMachine( 3615): make
,I/bluedroid( 3615): get_profile_interface a2dp
I/GKI_LINUX( 3615): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3615): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3615): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3615): classInitNative: succeeds
D/HidService( 3615): Received start request. Starting profile...
,I/bluedroid( 3615): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3615): classInitNative: succeeds
,D/HealthService( 3615): Received start request. Starting profile...
,I/bluedroid( 3615): get_profile_interface health
,I/BluetoothPanServiceJni( 3615): classInitNative(L105): succeeds
,D/BluetoothPan( 1020): BluetoothPAN Proxy object connected
D/PanService( 3615): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3615): initializeNative(L110): pan
,I/bluedroid( 3615): get_profile_interface pan
,D/BluetoothTethering( 1020): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1020): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@44241478
,I/BtGatt.JNI( 3615): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3615): handleDebugAction() action=null
,D/BtGatt.GattService( 3615): Received start request. Starting profile...
D/BtGatt.GattService( 3615): start()
,I/bluedroid( 3615): get_profile_interface gatt
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  457): NL - Read 1004 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1020): InitialState.processMessage what=4
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/BluetoothMapService( 3615): Received start request. Starting profile...
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothMapService( 3615): start()
,D/HeadsetPhoneState( 3615): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 3615): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3615): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3615): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/HeadsetPhoneState( 3615): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3615): Profile still not running:com.android.bluetooth.hdp.HealthService
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  277): NetlinkHandler, interfaceAdded
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
E/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  277): , Wifi = 0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  457): NL - Read 1004 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,D/BluetoothAdapterService( 3615): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3615): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3615): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 3615): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3615): enable
,I/bt_hci_bdroid( 3615): init
,I/bt_vendor( 3615): bt-vendor : init
I/bt_hci_bdroid( 3615): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3615): userial_init
I/bt_hwcfg( 3615): Starting hciattach daemon
,I/bt_hwcfg( 3615): try to set false
I/bt_hci_bdroid( 3615): bt_hc_worker_thread started
D/QsoftapCmd(  274): Got softap fwreload command we are passing on
D/SoftapController(  274): Softap fwReload - Ok
,I/bt_hwcfg( 3615): Starting hciattach daemon
,I/bt_hwcfg( 3615): try to set true
,I/ActivityManager( 1020): Killing 3181:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/qcom-bluetooth( 3680): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring down wlan0
,D/WifiService( 1020): New client listening to asynchronous messages
,I/qcom-bluetooth( 3687): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3688): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,V/BluetoothFtpReceiver( 3615): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 2025): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/qcom-bluetooth( 3690): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3691): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3692): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/Diag_Lib( 3694): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3694): Setting internal use port to rmnet0
E/Diag_Lib( 3694):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3694): Failed on DIAG init
E/Diag_Lib( 3694): linux_qmi_qmux_if_client_get_proc_name: pid=3694, proc_name=hci_qcomm_init
E/Diag_Lib( 3694): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3694): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3694): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
,E/Diag_Lib( 3694): qmi_client [3694]: successfully connected to server, attempt=1
E/Diag_Lib( 3694): linux_qmi_qmux_if_client_get_client_id [3694]: qmux_client_id=13
E/Diag_Lib( 3694): qmi_client [3694] 13: qmux_client ID is initialized
E/Diag_Lib( 3694): qmi_client [3694] 13: pipe() system call, fd[0]=10, fd[1]=11
E/Diag_Lib( 3694): qmi_client [3694] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3694): qmi_client [3694] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3694): Sending signal ...... to read cmd data 
E/Diag_Lib( 3694): qmi error code.........:0
E/Diag_Lib( 3694): qmi sys error code.........:0
,E/Diag_Lib( 3694): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3694): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3694): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3694): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3694): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3694): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3694): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3694): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3694): qmi_init:  Created client handle b71f7788
,E/Diag_Lib( 3694): qmi_client [3694] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3694): qmi_client [3694] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3694): Sending signal ...... to read cmd data 
E/Diag_Lib( 3694): qmi error code.........:0
,E/Diag_Lib( 3694): qmi sys error code.........:0
E/Diag_Lib( 3694): Setting the api flag to : 1
,E/Diag_Lib( 3694): qmi_client [3694] 13: sending 54 bytes on fd = 8
,E/WifiHW  ( 1020): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1020): ctrl_interface != /data/misc/wifi/sockets
,I/wpa_supplicant( 3697): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3697): rfkill: Cannot open RFKILL control device
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/rmt_storage(  416): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7c511d0
I/rmt_storage(  416): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  416): wakelock acquired: 1, error no: 42
,I/rmt_storage(  416): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1211822360)
E/Diag_Lib( 3694): qmi_client [3694] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3694):  API Flag .............. 1 
,E/Diag_Lib( 3694):  Message ID ............... 92 
E/Diag_Lib( 3697): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3697): Setting internal use port to rmnet0
,E/wpa_supplicant( 3697): baseband property is set to [msm]
,E/wpa_supplicant( 3697):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3697): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3697): card_info[i].card_state: 0x2
E/wpa_supplicant( 3697): card_info[i].error_code: 0x3
E/wpa_supplicant( 3697): SIM/USIM not ready
,E/wpa_supplicant( 3697): Error while reading SIM card status
,D/WifiStateMachine( 1020): setWifiState: enabling
,D/WifiStateMachine( 1020): Supplicant start successful
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1272): Active network info is not available
E/wpa_supplicant( 3697): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3697): card_info[i].card_state: 0x2
E/wpa_supplicant( 3697): card_info[i].error_code: 0x3
E/wpa_supplicant( 3697): SIM/USIM not ready
,I/wpa_supplicant( 3697): eap_proxy: Card not ready
,E/Diag_Lib( 3694): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3694): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3694): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3694): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3694): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3694): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3694): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3694): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3694): qmi_client [3694] 13: sending 880 bytes on fd = 8
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
E/Diag_Lib( 3694): qmi_client [3694] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3694): Sending signal ...... to read cmd data 
E/Diag_Lib( 3694): qmi error code.........:0
E/Diag_Lib( 3694): qmi sys error code.........:0
E/Diag_Lib( 3694): qmi_release: Released client handle ff
E/Diag_Lib( 3694): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3694,): Called qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3694): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3694): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3694): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3694): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3694): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3694): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3694): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3694): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3694): qmi_client [3694] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3694): qmi_client [3694] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3694): Sending signal ...... to read cmd data 
E/Diag_Lib( 3694): qmi error code.........:0
E/Diag_Lib( 3694): qmi sys error code.........:0
E/Diag_Lib( 3694): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3694] 13
E/Diag_Lib( 3694): qmi_client [3694] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3694): qmi_client [3694] 13: failed to locate client data
E/Diag_Lib( 3694): qmi_client [3694] 13: calling release of fd=8
E/Diag_Lib( 3694): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,D/WifiMonitor( 1020): startMonitoring(wlan0) with mConnected = false
,I/rmt_storage(  416): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  416): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  416): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1211822360) wakelock released: 1, error no: 0
I/rmt_storage(  416): 
,I/rmt_storage(  416): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7c511d0
,I/qcom-bluetooth( 3700): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3701): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3615): bluetooth satus is on
D/bt_userial_mct( 3615): userial_open(port:0)
,I/wpa_supplicant( 3697): Long line in configuration file truncated
,I/wpa_supplicant( 3697): rfkill: Cannot open RFKILL control device
I/bt_userial_vendor( 3615): Done intiailizing UART
I/bt_userial_vendor( 3615): Done intiailizing UART
I/bt_userial_mct( 3615): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/GKI_LINUX( 3615): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3615): btu_task pending for preload complete event
I/bt_vendor( 3615): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 3615): Entering userial_read_thread()
I/bt-btu  ( 3615): btu_task received preload complete event
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
I/        ( 3615): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3615): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3615): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3615): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3615): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3615): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3615): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3615): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3615): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3615): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3615): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3615): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3615): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3615): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3615): BTE_InitTraceLevels -- TRC_BTIF
,E/wpa_supplicant( 3697): COUNTRY Code Recived
,E/wpa_supplicant( 3697): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3697): baseband property is set to [msm]
,E/bt-btm  ( 3615): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f119049 
,E/bt-btm  ( 3615): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f119049 
,E/wpa_supplicant( 3697):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3697): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3697): card_info[i].card_state: 0x2
E/wpa_supplicant( 3697): card_info[i].error_code: 0x3
E/wpa_supplicant( 3697): SIM/USIM not ready
,E/wpa_supplicant( 3697): Error while reading SIM card status
,E/bt-btif ( 3615): Calling BTA_HhEnable
E/bt-btif ( 3615): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3615): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:1 len:6
E/wpa_supplicant( 3697): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3697): card_info[i].card_state: 0x2
E/wpa_supplicant( 3697): card_info[i].error_code: 0x3
E/wpa_supplicant( 3697): SIM/USIM not ready
,I/wpa_supplicant( 3697): eap_proxy: Card not ready
D/BluetoothAdapterProperties( 3615): Name is: XT1039
,I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3615): Scan Mode:21
I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3615): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:8 len:0
,I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:3 len:48
I/bte_conf( 3615): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothManagerService( 1020): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1020): Stored Bluetooth name: XT1039
,E/bt_mct  ( 3615): hci lib postload completed
I/bte_conf( 3615): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3615): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3615): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 3615): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3615): ScanMode =  21
D/BluetoothAdapterProperties( 3615): State =  11
D/BluetoothAdapterProperties( 3615): Setting state to 12
I/BluetoothAdapterState( 3615): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3615): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothPanServiceJni( 3615): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3615): Discoverable Timeout:120
D/BluetoothManagerService( 1020): Message: 60
D/BluetoothManagerService( 1020): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1020): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan( 1020): onBluetoothStateChange on: true
,D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1020): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1020): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
D/BluetoothManagerService( 1020): Bluetooth State Change Intent: 11 -> 12
,I/BluetoothAdapterState( 3615): Entering On State
,D/BluetoothAdapterService(1115473512)( 3615): Get Bonded Devices being called
,D/BluetoothAdapterService(1115473512)( 3615): Get Bonded Devices being called
,D/BluetoothManagerService( 1020): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService(1115473512)( 3615): Get Bonded Devices being called
,D/BluetoothMapService( 3615): onReceive
D/BluetoothMapService( 3615): STATE_ON
,D/BluetoothManagerService( 1020): Message: 40
D/BluetoothManagerService( 1020): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3615): Map Service startRfcommSocketListener
D/WifiStateMachine( 1020): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1020): invokeExitMethods: InitialState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1020): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131144
D/WifiStateMachine( 1020): processMsg: SupplicantStartingState
D/WifiStateMachine( 1020): deferMessage: msg=131144
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131085
D/WifiStateMachine( 1020): processMsg: SupplicantStartingState
D/WifiStateMachine( 1020): deferMessage: msg=131085
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131149
D/WifiStateMachine( 1020): processMsg: SupplicantStartingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1020): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131145
D/WifiStateMachine( 1020): processMsg: SupplicantStartingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131146
D/WifiStateMachine( 1020): processMsg: SupplicantStartingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: SupplicantStartingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: SupplicantStartingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147457
D/WifiStateMachine( 1020): processMsg: SupplicantStartingState
D/WifiStateMachine( 1020): Supplicant connection established
,D/WifiStateMachine( 1020): setWifiState: enabled
W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1272): Active network info is not available
,D/WifiConfigStore( 1020): Loading config and enabling all networks
,D/BluetoothMapService( 3615): Map Service initSocket
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3615): getBluetoothService() called with no BluetoothManagerCallback
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/qcom-bt-wlan-coex( 3715): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,E/WifiConfigStore( 1020): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3697): COUNTRY Code Recived -COUNTRY PL
,E/BluetoothServiceJni( 3615): SOCK FLAG = 1 ***********************
,D/BluetoothMapService( 3615): Accepting socket connection...
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3615): Scan Mode:21
,D/WifiStateMachine( 1020): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1020): invokeExitMethods: SupplicantStartingState
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1020): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1020): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1020): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3697): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3697): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1020): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1020): transitionTo: destState=DisconnectedState
,D/WifiP2pService( 1020): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring up p2p0
D/WifiStateMachine( 1020): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1020): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
,D/WifiMonitor( 1020): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1020): P2pEnablingState
D/WifiP2pService( 1020): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2p socket connection successful
D/WifiP2pService( 1020): P2pEnabledState
,D/WifiP2pService( 1020): sending p2p connection changed broadcast
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1020): invokeEnterMethods: DisconnectedState
,D/WifiP2pService( 1020): DeviceAddress: f4:f1:e1:5c:43:c8
,D/WifiP2pService( 1020): MCC mode enabled 0
,D/WifiP2pService( 1020): mP2pAutoConnectSupport = 0
,D/WifiP2pService( 1020): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1020): InactiveState
,D/WifiP2pService( 1020): InactiveState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131144
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131085
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131152
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): set country code PL
E/wpa_supplicant( 3697): COUNTRY Code Recived
E/wpa_supplicant( 3697): COUNTRY Code Recived
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131162
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): set frequency band 2
W/wpa_supplicant( 3697): wlan0: Failed to initiate AP scan
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/wpa_supplicant( 3697): COUNTRY Code Recived
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
E/wpa_supplicant( 3697): COUNTRY Code Recived
D/WifiStateMachine( 1020): handleMessage: E msg.what=131167
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiP2pService( 1020): InactiveState{ when=-5ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-5ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): InactiveState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/SharedPreferencesImpl( 1020): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=143371
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
,D/dalvikvm( 1020): GC_EXPLICIT freed 22868K, 65% free 17884K/50300K, paused 6ms+11ms, total 168ms
,W/ContextImpl( 3652): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService( 1020): Message: 20
,D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b92260:true
,D/BluetoothPbapService( 3615): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothPbapService( 3615): Handler(): got msg=1
,D/LocalBluetoothProfileManager( 3652): Adding local A2DP profile
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3615): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService( 1020): Message: 30
,E/BluetoothServiceJni( 3615): SOCK FLAG = 1 ***********************
,W/ContextImpl( 3652): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3652): Adding local HEADSET profile
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 3652): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 3652): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 3652): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3652): Adding local MAP profile
D/BluetoothMap( 3652): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 3652): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 3652): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3652): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3652): finishStartingService: stopping service
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/BluetoothAdapterService(1115473512)( 3615): Get Bonded Devices being called
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/BluetoothA2dp( 3652): Proxy object connected
,D/A2dpProfile( 3652): Bluetooth service connected
,D/BluetoothHeadset( 3652): Proxy object connected
,D/HeadsetProfile( 3652): Bluetooth service connected
,D/BluetoothInputDevice( 3652): Proxy object connected
,D/HidProfile( 3652): Bluetooth service connected
,D/BluetoothPan( 3652): BluetoothPAN Proxy object connected
,D/PanProfile( 3652): Bluetooth service connected
D/BluetoothMap( 3652): Proxy object connected
,D/MapProfile( 3652): Bluetooth service connected
,D/BluetoothMap( 3652): getConnectedDevices()
,D/BluetoothPbap( 3652): Proxy object connected
,D/PbapServerProfile( 3652): Bluetooth service connected
,V/BluetoothFtpReceiver( 3615): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3615): BluetoothFtpReceiver Start Service
D/AuthorizationBluetoothService( 2025): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2025): Proximity feature is not enabled.
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3615): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3615): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3615): Accept thread started.
V/BluetoothFtpService( 3615): Ftp Service onCreate
I/BluetoothFtpService( 3615): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3615): Starting FTP service
V/BluetoothFtpService( 3615): Ftp Service onStartCommand
,V/BluetoothFtpService( 3615): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3615): Handler(): got msg=1
V/BluetoothFtpService( 3615): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3615): Ftp Service initSocket
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3615): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3615): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3615): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3615): Run Accept thread
,D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
,I/MDMCTBK (  277): wifi_connect_to_supplicant, current pid is = 277
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
,E/MDMCTBK (  277): Attach monitor thread
I/MDMCTBK (  277): createWifiMonitorThread: Started the wifi monitor thread -1204591872
,D/MDMCTBK (  277): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/wpa_supplicant( 3697): wlan0: Failed to initiate AP scan
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  277): Event received = Failed to initiate AP scan
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledStateupdate channel list
,D/TCMD    (  457): NL - Read 56 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 c0:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 38:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 06:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 3 06:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 fe:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 fe:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 8e:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 8e:
D/MDMCTBK (  277): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 fc:
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 fc:
,I/wpa_supplicant( 3697): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  277): Event received = Trying to associate with
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3696): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 3696): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,E/wpa_supplicant( 3697): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,I/wpa_supplicant( 3697): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3697): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  457): NL - Read 312 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 88 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
I/wpa_supplicant( 3697): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  457): NL - Read 80 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 80 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  277): Event received = Associated with c0:ff:d4
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1020): processMsg: DisconnectedState
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1020): handleMessage: X
,D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 3697): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  277): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 3697): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  277): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  277):  STA Connected !!
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  277): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,I/MDMCTBK (  277): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0,
E/MDMCTBK (  277): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  277): get_freq !!, resp=0
I/MDMCTBK (  277): get_freq !!, Strip data
I/MDMCTBK (  277): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  277): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
,I/MDMCTBK (  277): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23,
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1204595976
I/MDMCTBK (  277): return from set_get_from_wpa_supplicant
D/MDMCTBK (  277): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE ,
E/MDMCTBK (  277): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  277): , reply_len: 3, ret: 0
E/MDMCTBK (  277): MdmCutbackHndler, resp=OK
E/MDMCTBK (  277): 
D/MDMCTBK (  277): wifi_set_tx_pwr: Exit
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: DisconnectedState
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=147459
D/WifiStateMachine( 1020): processMsg: DisconnectedState,
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): Network connection established
,D/WifiStateMachine( 1020): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine( 1020): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1020): invokeExitMethods: DisconnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1020): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1020): invokeEnterMethods: ObtainingIpState
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-23ms what=147462 obj=android.net.wifi.StateChangeResult@42805db0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196612
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ac5ee0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42ac5ee0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=147461
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 9
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 7 9
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 3 9e
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 fe
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 5 fe
D/TCMD    (  457): NL - Read 56 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 8e
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 6 8e
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 fc
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-ADDED 7 fc
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  277): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4291bb68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4291bb68 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@4291bb68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): handleMessage: X
,D/TCMD    (  457): NL - Read 60 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 20
,D/TCMD    (  457): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ObtainingIpState
D/WifiStateMachine( 1020): ObtainingIpState{ when=0 what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1020): processMsg: ObtainingIpState
,D/WifiStateMachine( 1020): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1020): DHCP successful
D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1020): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1020): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1020): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState enter
D/WifiStateMachine( 1020): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=151572
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1020): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1020): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=135190
D/WifiStateMachine( 1020): processMsg: VerifyingLinkState
D/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1020): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1020): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1020): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState enter
,D/WifiStateMachine( 1020): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1020): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1020): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1020): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1020): WiFi NOT Tethered!
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@4289e4f8
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1020): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1020): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1020): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131092
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1020): WiFi NOT Tethered!
,E/ConnectivityService( 1020): Unexpected mtu value: android.net.wifi.WifiStateTracker@4289e4f8
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_3_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi three bars."
D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1020): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1020): handleMessage: E msg.what=131215
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1020): handleMessage: X
D/ConnectivityService( 1020): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1020):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1020): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=true
,W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/        ( 1020): Setting time of day to sec=1449683873
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/        ( 1020): Unable to set rtc to 1449683873: Invalid argument
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1020): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3785 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/PollingManager( 1539): now: 357683 ,futureTime: 74394341
D/PollingManager( 1539): Polling alarm set to expire at: 74394341 Current Time: 357683
D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1539): registerApp(): CCE
I/CCE     ( 1539): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1539): Registering with Alarm Manager to restart CCE
,D/MMApiWebService( 1539): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
,D/CCE     ( 1539): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1539): isRequestAllowed(): already have outstanding request ... ignoring request
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1539): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/PollingManager( 1539): now: 357750 ,futureTime: 74394341
,D/PollingManager( 1539): Polling alarm set to expire at: 74394341 Current Time: 357750
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1539): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1539): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/OtaApp  ( 1539): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
D/MMApiWebService( 1539): generating token using payload instead of using session token
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/dalvikvm( 1020): Jit: resizing JitTable from 8192 to 16384
,D/OtaApp  ( 1539): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1539): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1020): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3821 uid=10056 gids={50056, 3003, 1028, 1015}
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,I/dalvikvm( 1374): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1374): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1374): VFY: replacing opcode 0x6e at 0x003d
,E/ActivityThread( 1374): Failed to find provider info for com.android.contacts.metadata
D/GpsLocationProvider( 1020): NTP server returned: 1449683870488 (Wed Dec 09 18:57:50 CET 2015) reference: 354835 certainty: 14 system time offset: -3202
,E/LocSvc_ApiV02( 1020): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/DelayedSyncController( 3821): Delaying sync.
,D/dalvikvm( 3785): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x427c5468, skipping init
I/openssl ( 3785): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3785): Crypto mode 0 already enabled
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3852 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3386:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/SyncManager( 1020): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 358112, reason: UserStart
,E/Auth.Api.Credentials( 1374): [CredentialSyncAdapter] Unknown sync event.
I/ActivityManager( 1020): Killing 3057:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 3852): mnc/mcc: 
,V/MmsConfig( 3852): tag: bool value: enabledMMS - true
V/MmsConfig( 3852): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3852): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 3852): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3852): tag: int value: defaultSMSMessagesPerThread - 500
,V/MmsConfig( 3852): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3852): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3852): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 3852): tag: int value: recipientLimit - 20
V/MmsConfig( 3852): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3852): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 3852): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3852): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3852): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3852): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 3852): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3852): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3852): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3871 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 3418:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1242): GC_EXPLICIT freed 1459K, 45% free 9517K/17224K, paused 2ms+4ms, total 60ms
,I/jxcore-log( 3565): Test app app.js loaded
I/jxcore-log( 3565): 
,I/chromium( 3565): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/dalvikvm( 1020): GC_EXPLICIT freed 1764K, 65% free 17877K/50300K, paused 4ms+11ms, total 102ms
,D/MobileConnectivityChangeReceiver( 3871): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3871): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3871): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3871): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3894 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3088:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1374): Checkin interval check for package: unspecified last checkin: 1449681276648 min interval config: 0 actual interval: 2597390
,I/CheckinService( 1374): Checking schedule, now: 1449683874072 next: 1449681306612
,I/CheckinService( 1374): active receiver: enabled
,I/CheckinService( 1374): Preparing to send checkin request
,I/EventLogService( 1374): Accumulating logs since 1449683734345
,D/DelayedSyncController( 3821): Delaying sync.
,I/CheckinRequestBuilder( 1374): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1020): New client listening to asynchronous messages
,E/ActivityThread( 1374): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromiumFactoryProvider( 3894): Binding Chromium to main looper Looper (main, tid 1) {427c2358}
,I/LibraryLoader( 3894): Expected native library version number "",actual native library version number ""
,I/chromium( 3894): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3894): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3894): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3894): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3894): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3894): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3894): Local Branch: 
I/Adreno-EGL( 3894): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3894): Local Patches: NONE
I/Adreno-EGL( 3894): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3894): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,V/GLSActivity( 2025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PhenotypeConfigurator( 1210): Scheduling Phenotype for one-off execution 2246 seconds from now (1449683874261)
,W/GAV2    ( 3894): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/GetConfigurationSnapshotOperation( 1210): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3894): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3938 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
I/PhenotypeFlagCommitter( 1210): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1210): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1210): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1210): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1210): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1210): Using platform SSLCertificateSocketFactory
,W/dalvikvm( 3938): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3938): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 3938): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3938): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3938): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 3938): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3938): install
,I/MultiDex( 3938): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 3938): loading existing secondary dex files
,I/MultiDex( 3938): load found 3 secondary dex files
,I/MultiDex( 3938): install done
,D/dalvikvm( 3938): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3938): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3938): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3938): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3938): VFY: unable to resolve instance field 36
,D/dalvikvm( 3938): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3938): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3938): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3938): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3938): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3938): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 3938): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427c7f28
D/dalvikvm( 3938): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427c7f28
,D/dalvikvm( 3938): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427c7f28, skipping init
,D/dalvikvm( 3938): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427c7f28
D/dalvikvm( 3938): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427c7f28
,V/JNIHelp ( 3938): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NSApplication( 3894): Starting up...
,I/ImageResourceManager( 3106): ImageResourceManager: uninitalized
D/dalvikvm( 3938): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427c7f28
D/dalvikvm( 3938): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427c7f28
D/dalvikvm( 3938): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427c7f28
,D/dalvikvm( 3938): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427c7f28
,I/iu.Environment( 3106): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3106): SYNC; picasa accounts
I/ActivityManager( 1020): Killing 3444:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1210): GC_CONCURRENT freed 1498K, 34% free 11436K/17224K, paused 5ms+21ms, total 65ms
,I/iu.UploadsManager( 3106): num queued entries: 0
,I/iu.UploadsManager( 3106): num updated entries: 0
,I/iu.SyncManager( 3106): NEXT; no task
,D/MMApiWSBase( 1539): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1539): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1539): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/iu.SyncManager( 1374): SYNC; picasa accounts
,D/NetworkLogImpl( 1374): Loaded NetworkSpeedPredictor
,D/Checkin ( 1539): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,I/iu.Environment( 1374): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SundryService( 1539): handleGetNotificationsResponse(): got 0; more=false
,I/iu.UploadsManager( 1374): num queued entries: 0
,I/iu.UploadsManager( 1374): num updated entries: 0
,I/iu.SyncManager( 1374): NEXT; no task
,D/dalvikvm( 1374): GC_CONCURRENT freed 1665K, 30% free 12068K/17224K, paused 4ms+5ms, total 65ms
,I/ProviderInstaller( 3938): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 2025): GC_EXPLICIT freed 1533K, 41% free 10280K/17224K, paused 2ms+4ms, total 34ms
,D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
I/openssl ( 3785): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3785): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3871): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3871): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3106): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 3938): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 3938): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3938): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 3938): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 3938): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3938): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 3106): GC_CONCURRENT freed 617K, 5% free 16454K/17224K, paused 4ms+2ms, total 25ms
I/ActivityManager( 1020): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3971 uid=10007 gids={50007, 3003}
,I/dalvikvm( 3938): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3938): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 3938): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 3938): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 3938): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3938): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 3938): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3938): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 3938): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 3938): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 3938): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/MMApiProvisionService( 1539): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"160382","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1539): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1539): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1539): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1539): handleResponse(): Session Expiration alarm set to expire at: Fri Dec 11 15:30:56 CET 2015
,D/MMApiProvisionService( 1539): _setMMApiCredInfo: storing credential info 
,E/MMApiProvisionService( 1539): handleResponse(): no settings sent by the server:
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,I/GCM     ( 2025): GCM config loaded
,D/ExtensionsFactory( 3971): No custom extensions.
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): Level3 Library Nov 20 2013 18:09:31
,I/ActivityManager( 1020): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3992 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1020): Killing 3127:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DrmWidevineDash(  282): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
E/QSEECOMAPI: (  282): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  282): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
E/QSEECOMAPI: (  282): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  282): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  282): App is not loaded in QSEE
I/ActivityManager( 1020): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4005 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3652:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  279): GC_EXPLICIT freed 44K, 48% free 9012K/17224K, paused 2ms+2ms, total 22ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/QSEECOMAPI: (  282): Loaded image: APP id = 3
D/DrmWidevineDash(  282): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5214000
,E/DrmWidevineDash(  282): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5214000
,D/DrmWidevineDash(  282): OEMCrypto_Initialize exit returns 0
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,D/DrmWidevineDash(  282): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  282): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  282): calling OEMCrypto_IsKeyboxValid...
,D/WifiService( 1020): Client connection lost with reason: 4
,D/DrmWidevineDash(  282): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  282): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  282): CdmEngine::OpenSession
,D/DrmWidevineDash(  282): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  282): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  282): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetDeviceID...
,V/AlarmClock( 3992): AlarmInitReceiver android.intent.action.TIME_SET
,I/dalvikvm( 1210): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1210): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1210): VFY: replacing opcode 0x6e at 0x003d
D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=2197209289
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/CalendarProvider2( 4005): Created com.android.providers.calendar.CalendarAlarmManager@427df120(com.android.providers.calendar.CalendarProvider2@427d6cd8)
,I/AlarmClock( 3992): Displaying next alarm time: ''
,V/AlarmClock( 3992): AlarmInitReceiver finished
,I/ActivityManager( 1020): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4023 uid=10098 gids={50098}
,D/dalvikvm( 4023): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x427bfe58, skipping init
D/TimeService( 4023): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683875036
D/        ( 4023): TimeServiceNative: User Time to be set is 1449683875037
D/QC-time-services( 4023): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4023): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 4023): Lib:time_genoff_operation: pargs->ts_val = 1449683875037
D/QC-time-services(  393): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4023): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  393): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683875037
D/QC-time-services(  393): Daemon:genoff_opr: Base = 2, val = 1449683875037, operation = 0
D/QC-time-services(  393): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/9/115 17:52:1
D/QC-time-services(  393): Daemon:Value read from RTC seconds = 1449683521000
D/QC-time-services(  393): Daemon:new time 1449683875037 
D/QC-time-services(  393): Daemon: delta 354037 genoff 354037 
D/QC-time-services(  393): Daemon:genoff_persistent_update: Writing genoff = 354037 to memory
D/QC-time-services(  393): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  393): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  393): Updating the TOD offset
D/QC-time-services(  393): Daemon:genoff_persistent_update: Writing genoff = 354037 to memory
D/QC-time-services(  393): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  393): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  393): Daemon:Update to modem bit set
D/QC-time-services(  393): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 4023): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  393): Daemon: Base = 2, Value being sent to MODEM = 18446743757745105653
,I/ActivityManager( 1020): Killing 3785:android.process.media/u0a18 (adj 15): empty #9
E/QC-time-services(  393): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  393): Daemon: Time-services: Waiting to acceptconnection
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1539): GC_CONCURRENT freed 2101K, 38% free 10717K/17224K, paused 3ms+8ms, total 38ms
,D/dalvikvm( 3938): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429be9d8
,I/CheckinService( 1374): Checkin interval check for package: unspecified last checkin: 1449681276648 min interval config: 0 actual interval: 2598441
D/dalvikvm( 3938): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429be9d8
,D/dalvikvm( 3938): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x429be9d8, skipping init
,D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1539): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1539): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1539
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): calling OEMCrypto_CloseSession. SID = 1
,D/OtaApp  ( 1539): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1539): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1020): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1539
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession returns 0
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/IInputConnectionWrapper( 3565): showStatusIcon on inactive InputConnection
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/LaunchCheckinHandler( 1020): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,111
I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/DEBUG   ( 1539): Received intent : com.motorola.ccc.notification.action.NOTIFY
D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SundryService( 1539): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1539): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
,I/ActivityManager( 1020): Activity reported stop, but no longer stopping: ActivityRecord{42953220 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,D/NativeLibraryUtils( 3938): Install completed successfully. count=14 extracted=0
,D/WearableService( 1210): callingUid 10022, callindPid: 1210
,D/LocationInitializer( 1374): Restart initialization of location
,E/MDM     ( 1210): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 2025): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2025): Proximity feature is not enabled.
,W/GCoreFlp( 1210): No location to return for getLastLocation()
,W/FusedLocationProvider( 1210): location=null
,V/GLSActivity( 2025): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  282): CdmEngine::OpenSession
,D/DrmWidevineDash(  282): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  282): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  282): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  282): calling OEMCrypto_GenerateNonce. SID = 1
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=3165893647
D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 7
D/DrmWidevineDash(  282): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 1020): GC_EXPLICIT freed 662K, 65% free 17895K/50300K, paused 4ms+10ms, total 116ms
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,D/DEBUG   ( 1539): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1285): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1285): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/ContextImpl( 1539): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1539): bindWebServices(): registering our AIDL callback...
,D/GetNotificationsWS( 1539): onServiceConnected()
,D/GetNotificationsWS( 1539): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1539): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1539): Received shoulder tap
,D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1539): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1539): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession returns 0
,W/Settings( 3938): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 3938): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4055): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 3938): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3938): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 99ms
,I/Adreno-EGL( 3938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3938): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3938): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3938): Local Branch: 
I/Adreno-EGL( 3938): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3938): Local Patches: NONE
I/Adreno-EGL( 3938): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CalendarProvider2( 4005): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4005): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3971): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3971): 0 Action = android.intent.action.PROVIDER_CHANGED
,I/Adreno-EGL( 3938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3938): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3938): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3938): Local Branch: 
I/Adreno-EGL( 3938): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3938): Local Patches: NONE
I/Adreno-EGL( 3938): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/MMApiWSBase( 1539): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1539): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1539): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1539): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1539): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1539): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1539): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1539): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,I/Adreno-EGL( 3938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3938): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3938): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3938): Local Branch: 
I/Adreno-EGL( 3938): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3938): Local Patches: NONE
I/Adreno-EGL( 3938): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3938): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3938): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3938): Local Branch: 
I/Adreno-EGL( 3938): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3938): Local Patches: NONE
I/Adreno-EGL( 3938): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1374): Classify the device as Phone.
,I/CheckinTask( 1374): Sending checkin request (11772 bytes)
,I/CheckinRequestBuilder( 1374): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1374): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1374): Classify the device as Phone.
,I/CheckinTask( 1374): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1374): Checking schedule, now: 1449683878175 next: 1450276948165
,I/CheckinService( 1374): active receiver: disabled
,D/CheckinService( 1374): Recording last checkin time for package unspecified as 1449683878223
,D/GCM     ( 2025): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1374): GC_CONCURRENT freed 2072K, 31% free 12043K/17224K, paused 5ms+5ms, total 40ms
,D/dalvikvm( 1374): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/SQLiteConnectionPool( 1374): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/GAV2    ( 3894): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1020): sending alarm Alarm{42d12988 type 3 android}
,I/GlobalDismissManager( 3971): no sender configured
,D/AlertService( 3971): Beginning updateAlertNotification
,D/AlertService( 3971): No fired or scheduled alerts
,D/AlertService( 3971): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3971): No events found starting within 1 week.
I/ActivityManager( 1020): Killing 3852:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Killing 3871:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1020): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1020): Checking http://216.58.209.46/generate_204
,W/ActivityThread( 1020): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1020): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1020): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1020): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1020): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1020): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4096 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/Launcher( 1299): Deferring update until onResume
,I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,I/GCoreNlp( 1210): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4096): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4096): MmsConfig.loadMmsSettings
I/Babel   ( 4096): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4096): MmsConfig.loadFromDatabase
,E/Babel   ( 4096): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4096): MmsConfig.loadFromResources
,E/Babel   ( 4096): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4096): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4096): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1020): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4133 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 3821:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4153 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3894:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2195): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/dalvikvm( 3106): GC_FOR_ALLOC freed 47K, 5% free 16417K/17224K, paused 12ms, total 12ms
,I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4171 uid=10038 gids={50038, 3003, 1028, 1015}
I/dalvikvm-heap( 3106): Grow heap (frag case) to 19.802MB for 1821008-byte allocation
,I/ActivityManager( 1020): Killing 4005:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3106): GC_FOR_ALLOC freed 2K, 5% free 18195K/19004K, paused 15ms, total 15ms
,I/ContactLocale( 4133): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4171): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4171): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4171): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2195): UpdateCorporaTask done [took 228 ms] updated apps [took 228 ms] 
,I/dalvikvm( 4171): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4171): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4171): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4171): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4171): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4171): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4171): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4171): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4171): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4171): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4171): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4171): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4171): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4171): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4171): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4206 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/dalvikvm( 4171): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4171): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4171): Skipping gmscore version check
,D/Finsky  ( 4171): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4171): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4171): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4171): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4171): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1020): Killing 4023:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1374): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1374): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1374): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4206): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x427c7198, skipping init
I/openssl ( 4206): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4206): Crypto mode 0 already enabled
,I/ActivityManager( 1020): Killing 3992:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Finsky  ( 4171): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4171): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1374): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,I/Icing   ( 1374): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449683886
,I/jxcore-log( 3565): Toggling radios to false
I/jxcore-log( 3565): 
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1020): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@43e11c90 mBinding = false
,D/BluetoothManagerService( 1020): Message: 2
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,D/BluetoothManagerService( 1020): Sending off request.
D/BluetoothAdapterState( 3615): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3615): Setting state to 13
I/BluetoothAdapterState( 3615): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3615): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterProperties( 3615): onBluetoothDisable()
I/BluetoothAdapterState( 3615): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 3615): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3615): Scan Mode:21
D/BluetoothAdapterState( 3615): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 3615): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 3615): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3615): bta_jv_rfcomm_stop_server
E/bt-btif ( 3615): bta_jv_rfcomm_stop_server
,E/bt-btif ( 3615): bta_jv_rfcomm_stop_server
W/bt-btif ( 3615): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 3615): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3615): L2CAP - PSM: 0x0017 not found for deregistration
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3615): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothManagerService( 1020): Message: 60
D/BluetoothManagerService( 1020): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService( 1020): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3615): onReceive
,D/BluetoothMapService( 3615): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 3615): MAP Service closeService in
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/btif_config_util( 3615): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager( 1020): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4248 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/Settings( 1258): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiService( 1020): setWifiEnabled: false pid=3565, uid=10455
E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 4248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService( 1020): Message: 20
,D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a7bb78:true
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 4248): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 4248): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 4248): Adding local MAP profile
D/BluetoothMap( 4248): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 4248): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1020): Message: 30
,W/ContextImpl( 4248): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4248): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4248): finishStartingService: stopping service
,D/BluetoothInputDevice( 4248): Proxy object connected
D/HidProfile( 4248): Bluetooth service connected
,D/BluetoothPan( 4248): BluetoothPAN Proxy object connected
D/PanProfile( 4248): Bluetooth service connected
D/BluetoothMap( 4248): Proxy object connected
D/MapProfile( 4248): Bluetooth service connected
,D/BluetoothMap( 4248): getConnectedDevices()
,D/BluetoothMap( 4248): Bluetooth is Not enabled
,D/BluetoothPbap( 4248): Proxy object connected
,D/PbapServerProfile( 4248): Bluetooth service connected
I/ActivityManager( 1020): Killing 3971:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1020): GC_EXPLICIT freed 1739K, 65% free 17967K/50300K, paused 28ms+11ms, total 133ms
,W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/jxcore-log( 3565): Radios toggled
I/jxcore-log( 3565): 
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131084
D/WifiStateMachine( 1020): processMsg: ConnectedState
D/WifiStateMachine( 1020): processMsg: L2ConnectedState
D/WifiStateMachine( 1020): processMsg: ConnectModeState
D/WifiStateMachine( 1020): processMsg: DriverStartedState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1020): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1020): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
,W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiP2pService( 1020): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/Settings( 1258): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TCMD    (  457): NL - Read 60 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 21
,D/TCMD    (  457): Listening for incoming client connection request
,D/WifiStateMachine( 1020): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
I/BtOppRfcommListener( 3615): stopping Accept Thread
,I/BtOppRfcommListener( 3615): BluetoothSocket listen thread finished
,D/BluetoothPbapService( 3615): action: android.bluetooth.adapter.action.STATE_CHANGED
D/WifiStateMachine( 1020): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1020): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiMetrics( 1020): connected time updated 21545
D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1020): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1020): invokeExitMethods: ConnectModeState
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): invokeExitMethods: DriverStartedState
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1020): Attempting to switch to ETHERNET
I/bt_hwcfg( 3615): hw_epilog_process
W/bt-btif ( 3615): ag scb idx 1 not allocated
E/bt-btif ( 3615): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3615): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3615): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3615): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3615): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3615): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3615): L2CAP - PSM: 0x0017 not found for deregistration
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine( 1020): Unexpected BatchedScanResults :OK
,D/WifiService( 1020): New client listening to asynchronous messages
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1020): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131216
D/WifiStateMachine( 1020): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1020): processMsg: SupplicantStartedState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
D/WifiP2pService( 1020): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): P2pDisablingState
D/WifiP2pService( 1020): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): p2p socket connection lost
D/WifiP2pService( 1020): P2pDisabledState
D/WifiStateMachine( 1020): handleMessage: E msg.what=131205
,D/ConnectivityService( 1020): resetConnections(wlan0, 3)
D/WifiStateMachine( 1020): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1020): transitionTo: destState=SupplicantStoppingState
D/NetUtils( 1020): android_net_utils_resetConnections in env=0x611cb6c0 clazz=0x65b00001 iface=wlan0 mask=0x3
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1020): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1020): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1020): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1020): Stopping DHCP and clearing IP
D/WifiStateMachine( 1020): setSuspendOptimizationsNative: 1 true
D/BluetoothPbap( 4248): Proxy object disconnected
D/PbapServerProfile( 4248): Bluetooth service disconnected
V/BluetoothFtpReceiver( 3615): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
I/bt_hwcfg( 3615): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 3615): bt_hc_worker_thread exiting
D/bt_userial_mct( 3615): userial_close
I/bt_userial_mct( 3615): exiting userial_read_thread
D/bt_userial_mct( 3615): Leaving userial_evt_read_thread()
D/AuthorizationBluetoothService( 2025): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/NativeCrypto( 2025): Read error: ssl=0x615e4cb8: I/O error during system call, Connection timed out
V/NativeCrypto( 2025): SSL shutdown failed: ssl=0x615e4cb8: I/O error during system call, Broken pipe
D/WifiP2pService( 1020): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1020): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1020): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1020): stopping supplicant
D/WifiStateMachine( 1020): setWifiState: disabling
D/Checkin ( 1020): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1272): Active network info is not available
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  604): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  604): [WwanPosMgr] handleConnectivtyStatusChange failed
D/WifiStateMachine( 1020): handleMessage: X
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1020): Attempting to switch to mobile
D/ConnectivityService( 1020): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1020): Attempting to switch to ETHERNET
,E/XTCC-3.0.0.2(  604): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  604): [CSMgr] handleConnectivtyStatusChange failed
,D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
,I/wpa_supplicant( 3697): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiStateMachine( 1020): handleMessage: E msg.what=147460
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/Tethering( 1020): InitialState.processMessage what=4
,D/Tethering( 1020): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/WifiStateMachine( 1020): handleMessage: E msg.what=147462
D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/WifiStateMachine( 1020): handleMessage: X
D/MDMCTBK (  277): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  277):  STA Disconnected !!
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): get_property_value, Enter
I/MDMCTBK (  277): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  277): get_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/WifiStateMachine( 1020): handleMessage: E msg.what=131101
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  277): Event received = CTRL-EVENT-STATE-CHANGE 
D/BTSNOOP-DISP( 3615): btsnoop_close
I/bt_vendor( 3615): cleanup
I/bt_hwcfg( 3615): Starting hciattach daemon
I/bt_hwcfg( 3615): try to set false
I/GKI_LINUX( 3615): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3615): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 3615): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
D/Nat464Xlat( 1020): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1285): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1285): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1285): onReceive() - done, currentInetCondition=0
D/BluetoothAdapterState( 3615): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3615): Received stop request...Stopping profile...
D/BluetoothHeadset( 1242): Proxy object disconnected
D/BluetoothHeadset( 1242): Proxy object disconnected
D/BluetoothHeadset( 1020): Proxy object disconnected
D/BluetoothHeadset( 1242): Proxy object disconnected
D/A2dpService( 3615): Received stop request...Stopping profile...
D/A2dpStateMachine( 3615): Exit Disconnected: -1
D/BluetoothAdapterState( 3615): Stopping profile services that were post enabled
D/BluetoothA2dp( 1020): Proxy object disconnected
D/HidService( 3615): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4248): Proxy object disconnected
D/HidProfile( 4248): Bluetooth service disconnected
D/HealthService( 3615): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3615): Profile still running: com.android.bluetooth.hdp.HealthService
D/PanService( 3615): Received stop request...Stopping profile...
D/BluetoothTethering( 1020): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1020): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1020): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@44241478
D/BluetoothTethering( 1020): got CMD_CHANNEL_DISCONNECTED
D/BluetoothPan( 1020): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 4248): BluetoothPAN Proxy object disconnected
D/PanProfile( 4248): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 3615): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3615): Cleaning up Bluetooth Handsfree callback object
D/BtGatt.DebugUtils( 3615): handleDebugAction() action=null
D/BtGatt.GattService( 3615): Received stop request...Stopping profile...
D/BtGatt.GattService( 3615): stop()
D/BluetoothAdapterService( 3615): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 3615): Received stop request...Stopping profile...
D/BluetoothMapService( 3615): stop()
D/BluetoothMapService( 3615): MAP Service closeService in
D/BluetoothMap( 4248): Proxy object disconnected
D/MapProfile( 4248): Bluetooth service disconnected
I/GKI_LINUX( 3615): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3615): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3615): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService( 3615): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3615): Cleaning up Bluetooth HID Interface...
I/wpa_supplicant( 3697): eap_proxy Deinitialzed
W/bt-btif ( 3615): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3615): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3615): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3615): Cleaning up Bluetooth Health Interface...
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK ,(  277): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 4
W/BluetoothHealthServiceJni( 3615): Cleaning up Bluetooth Health object
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  277): Event received = CTRL-EVENT-BSS-REMOVED 6
D/BluetoothAdapterService( 3615): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3615): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3615): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 3615): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3615): cleanup()
D/BluetoothAdapterState( 3615): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 3615): MAP Service closeService in
D/BluetoothAdapterProperties( 3615): Setting state to 10
I/BluetoothAdapterState( 3615): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3615): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 3615): Entering OffState
D/BluetoothManagerService( 1020): Message: 60
D/BluetoothManagerService( 1020): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1020): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothPan( 1020): onBluetoothStateChange on: false
D/BluetoothMap( 4248): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1020): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1020): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 4248): onBluetoothStateChange: up=false
D/BluetoothPbap( 4248): onBluetoothStateChange: up=false
D/BluetoothPan( 4248): onBluetoothStateChange on: false
D/BluetoothManagerService( 1020): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1020): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@43e11c90 mBinding = false
D/BluetoothManagerService( 1020): Sending unbind request.
D/BluetoothAdapterService( 3615): Cleaning up adapter native....
I/GKI_LINUX( 3615): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3615): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 3615): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3615): cleanupNative: return from cleanup
D/BluetoothAdapterService( 3615): Done cleaning up adapter native....
D/BluetoothAdapterService(1115473512)( 3615): ****onDestroy()********
D/WifiStateMachine( 1020): handleMessage: E msg.what=196614
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/BluetoothManagerService( 1020): Bluetooth State Change Intent: 13 -> 10
D/BtGatt.GattService( 3615): cleanup()
W/bt-btif ( 3615): GATTC Module not enabled/already disabled
W/bt-btif ( 3615): GATTS Module not enabled/already disabled
D/BluetoothAdapter( 1081): 1116948248: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1210): 1118840680: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1210): 1118840680: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
W/ContextImpl( 4248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/DockEventReceiver( 4248): finishStartingService: stopping service
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
D/BluetoothAdapter( 4248): 1115512896: getState() :  mService = null. Returning STATE_OFF
V/BluetoothFtpReceiver( 3615): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3615): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 3615): Ftp Service onDestroy
V/BluetoothFtpService( 3615): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3615): Shutdown
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
I/wpa_supplicant( 3697): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  277):  Wpa Supplicant Exiting !!
D/MDMCTBK (  277): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  277): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  277): wifi_close_sockets: Exit
D/WifiStateMachine( 1020): handleMessage: E msg.what=147458
D/WifiStateMachine( 1020): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1020): Supplicant connection lost
D/AuthorizationBluetoothService( 2025): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1020): Killing 3938:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4289 uid=10016 gids={50016, 3002}
,D/Checkin ( 4289): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
I/ActivityManager( 1020): Killing 4096:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiStateMachine( 1020): setWifiState: disabled
D/WifiStateMachine( 1020): transitionTo: destState=InitialState
D/WifiStateMachine( 1020): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1020): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1020): invokeExitMethods: SupplicantStoppingState
,D/WifiStateMachine( 1020): moveTempStackToStateStack: i=0,j=1
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,D/WifiStateMachine( 1020): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1020): invokeEnterMethods: InitialState
,W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1272): Active network info is not available
W/Settings( 1210): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/XTCC-3.0.0.2(  604): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  604): [WwanPosMgr] handleConnectivtyStatusChange failed
,D/BluetoothAdapter( 4248): 1115512896: getState() :  mService = null. Returning STATE_OFF
,E/XTCC-3.0.0.2(  604): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  604): [CSMgr] handleConnectivtyStatusChange failed
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/NetlinkEvent(  274): Unexpected netlink message. type=0x11
W/Netd    (  274): No subsystem found in netlink event
D/TCMD    (  457): NL - Read 444 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 17
D/TCMD    (  457): Listening for incoming client connection request
,I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
,I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
,E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,D/NetlinkEvent(  274): Unexpected netlink message. type=0x11
W/Netd    (  274): No subsystem found in netlink event
D/TCMD    (  457): NL - Read 444 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 17
D/TCMD    (  457): Listening for incoming client connection request
I/MDMCTBK (  277): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  277): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  277): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  277): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
I/MDMCTBK (  277): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  277): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  277): set_property_value, Enter
I/MDMCTBK (  277): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  277): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  277): set_property_value, Exit
E/MDMCTBK (  277): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1020): handleMessage: X
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131208
D/WifiStateMachine( 1020): processMsg: InitialState
D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131208
D/WifiStateMachine( 1020): processMsg: InitialState
,D/WifiStateMachine( 1020): processMsg: DefaultState
D/WifiStateMachine( 1020): handleMessage: X
D/WifiStateMachine( 1020): handleMessage: E msg.what=131208
D/WifiStateMachine( 1020): processMsg: InitialState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,D/Checkin ( 2163): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  277): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  277): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
,I/MDMCTBK (  277): checkDefaultInst, pid match
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1020): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1020): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1272): Active network info is not available
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1539): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1539): [debug] > CusSM.onRadioDown
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1272): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1020): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1272): Active network info is not available
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1539): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4323 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,V/MmsConfig( 4323): mnc/mcc: 
,V/MmsConfig( 4323): tag: bool value: enabledMMS - true
V/MmsConfig( 4323): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4323): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4323): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4323): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4323): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 4323): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4323): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4323): tag: int value: recipientLimit - 20
V/MmsConfig( 4323): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4323): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4323): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4323): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 4323): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4323): tag: bool value: smsForceShowEncodingMenu - true
,V/MmsConfig( 4323): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4323): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4323): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1020): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4341 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1020): Killing 4133:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4341): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4341): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4341): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4341): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4354 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 4153:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 3ms+3ms, total 28ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4368 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1020): Killing 3106:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4368): Binding Chromium to main looper Looper (main, tid 1) {427bbcd8}
,I/LibraryLoader( 4368): Expected native library version number "",actual native library version number ""
,I/chromium( 4368): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4368): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4368): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4368): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4368): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4368): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4368): Local Branch: 
I/Adreno-EGL( 4368): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4368): Local Patches: NONE
I/Adreno-EGL( 4368): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4368): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4368): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4368): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4368): Starting up...
,I/ActivityManager( 1020): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4410 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1020): Killing 4171:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ImageResourceManager( 4410): ImageResourceManager: uninitalized
,I/ActivityManager( 1020): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4428 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/iu.Environment( 4410): update battery state; isPlugged? true*
I/iu.Environment( 4410): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 4410): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1020): Killing 3615:com.android.bluetooth/1002 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Killing 4289:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1374): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1539): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1539): bindWebServices(): registering our AIDL callback...
,I/iu.UploadsManager( 1374): num queued entries: 0
,I/iu.UploadsManager( 1374): num updated entries: 0
,I/iu.SyncManager( 1374): NEXT; no task
,D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1539): onServiceConnected()
,D/GetNotificationsWS( 1539): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4341): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4341): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4410): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 375K, 5% free 16405K/17224K, paused 15ms, total 16ms
,I/dalvikvm-heap( 4410): Grow heap (frag case) to 19.790MB for 1821008-byte allocation
,I/iu.UploadsManager( 4410): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/iu.FingerprintManager( 4410): Start processing all media
,I/iu.FingerprintManager( 4410): Start processing media store URI: content://media/external/images/media
,I/ContactLocale( 4428): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 4410): GC_FOR_ALLOC freed 19K, 5% free 18196K/19004K, paused 19ms, total 19ms
,I/iu.FingerprintManager( 4410): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4410): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.UploadsManager( 4410): End new media; added: 0, uploading: 0, time: 103 ms
,I/iu.FingerprintManager( 4410): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 4410): Finished generating fingerprints; 0.039 seconds
,I/iu.FingerprintManager( 4410):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/WifiP2pService( 1020): P2pDisabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1020): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1020): processMsg: InitialState
D/WifiStateMachine( 1020): processMsg: DefaultState
,D/WifiStateMachine( 1020): handleMessage: X
,V/AlarmManager( 1020): sending alarm Alarm{44e4ae00 type 2 com.android.keyguard}
,I/GAV2    ( 4368): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 1020): sending alarm Alarm{44e66420 type 2 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{44e664f8 type 3 android}
,D/ConnectivityService( 1020): NetTransition Wakelock for ConnectedState released by timeout
,V/AlarmManager( 1020): sending alarm Alarm{44e79728 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44f3cd90 type 1 com.android.deskclock}
,I/ActivityManager( 1020): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4473 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1020): Killing 4248:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1020): Client connection lost with reason: 4
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{429848d8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4289b3a8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44241cc8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42fe2168 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42987308 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{429233e0 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,V/AlarmManager( 1020): sending alarm Alarm{4451ee98 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4418b960 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4365ecc0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42890750 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{430429c8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4454bb78 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44273af8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43002248 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{442420f0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444c9190 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43009de0 type 1 com.android.deskclock}
,V/AlarmManager( 1020): sending alarm Alarm{4453aa58 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43037b68 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44fa5160 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,V/AlarmManager( 1020): sending alarm Alarm{42ffebb8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42953fa0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43992628 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{439dcd68 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4311d360 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4465afd0 type 3 android}
,I/ProcessStatsService( 1020): Prepared write state in 36ms
,I/ProcessStatsService( 1020): Prepared write state in 11ms
,I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-36-08.bin
,V/AlarmManager( 1020): sending alarm Alarm{4398a5c8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43679ab8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{444ddbf8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44599450 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4537): 
D/AndroidRuntime( 4537): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4537): CheckJNI is OFF
D/dalvikvm( 4537): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4537): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4537): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4537): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4537): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4537): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4537): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4537): failed to load memtrack module: -2
D/AndroidRuntime( 4537): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10455 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 3565:com.test.thalitest/u0a455 (adj 9): stop com.test.thalitest
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020):   Force finishing activity ActivityRecord{44e98628 u0 com.test.thalitest/.MainActivity t3}
I/WindowState( 1020): WIN DEATH: Window{44e2e938 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1020): Client connection lost with reason: 4
W/PackageSettings( 1020): Skipping PackageSetting{42a83258 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10455 user=0: pkg removed
D/dalvikvm( 2163): GC_EXPLICIT freed 6109K, 44% free 9753K/17224K, paused 16ms+6ms, total 61ms
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
W/GeofencerStateMachine( 1210): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1299): GC_EXPLICIT freed 2892K, 33% free 11592K/17224K, paused 22ms+5ms, total 136ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
D/dalvikvm( 1020): GC_EXPLICIT freed 1787K, 65% free 18087K/50300K, paused 6ms+14ms, total 145ms
D/dalvikvm( 2195): GC_EXPLICIT freed 2675K, 44% free 9777K/17224K, paused 3ms+9ms, total 146ms
I/Launcher( 1299): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
D/VoicemailCleanupService( 4428): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1374): GC_EXPLICIT freed 1644K, 31% free 11930K/17224K, paused 21ms+6ms, total 185ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4565 uid=10033 gids={50033, 3003, 1028, 1015}
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449685669
I/Launcher( 1299): Deferring update until onResume
I/LatinIME:LogUtils( 1192): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449685669
I/InternalIcingCorporaPro( 2195): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/ActivityManager( 1020): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4582 uid=10059 gids={50059, 3003, 1028, 1015}
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10455 #1
I/ActivityManager( 1020): Killing 4323:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1020): GC_EXPLICIT freed 768K, 65% free 17954K/50300K, paused 12ms+15ms, total 219ms
I/InternalIcingCorporaPro( 2195): UpdateCorporaTask done [took 110 ms] updated apps [took 110 ms] 
D/AndroidRuntime( 4537): Shutting down VM
D/dalvikvm( 4537): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
W/ActiveOrDefaultContextProvider( 4582): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4606 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/GAV2    ( 4582): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4625 uid=10038 gids={50038, 3003, 1028, 1015}
W/FileUtils( 4606): Failed to chmod(/data/data/com.android.keychain/databases/grants.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 4606): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 4606): threadid=10: thread exiting with uncaught exception (group=0x41ef0d40)
E/AndroidRuntime( 4606): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4606): Process: com.android.keychain, PID: 4606
E/AndroidRuntime( 4606): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4606): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4606): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:288)
E/AndroidRuntime( 4606): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4606): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4606): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4606): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 4606): Sending signal. PID: 4606 SIG: 9
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more
I/ActivityManager( 1020): Process com.android.keychain (pid 4606) has died.
W/ActivityManager( 1020): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/dalvikvm( 4625): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4625): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4625): VFY: replacing opcode 0x6e at 0x000e
D/Finsky  ( 4625): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/

```
