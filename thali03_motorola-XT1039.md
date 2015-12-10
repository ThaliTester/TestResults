#### Test 50650278c17c777_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of /dev/log/system
W/SocketClient(  270): write error (Broken pipe)
,D/AndroidRuntime( 3542): 
D/AndroidRuntime( 3542): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3542): CheckJNI is OFF
D/dalvikvm( 3542): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3542): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3542): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3542): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3542): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3542): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3542): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3542): failed to load memtrack module: -2
D/AndroidRuntime( 3542): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3542
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3559 uid=10457 gids={50457, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3542): Shutting down VM
D/dalvikvm( 3542): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  275): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 24ms
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
V/WebViewChromiumFactoryProvider( 3559): Binding Chromium to main looper Looper (main, tid 1) {4239a950}
I/LibraryLoader( 3559): Expected native library version number "",actual native library version number ""
I/chromium( 3559): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3559): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4418e878:true
D/BluetoothAdapter( 3559): 1111158624: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3559): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3559): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3559): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3559): Local Branch: 
I/Adreno-EGL( 3559): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3559): Local Patches: NONE
I/Adreno-EGL( 3559): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3559): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3559): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3559): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3559): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3559): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3559): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3559): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3559): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3559): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3559): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3559): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3559): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3559): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3559): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3559): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3559): CordovaWebView is running on device made by: motorola
,I/SFPerfTracer(  274):      triggers: (rate: 2:28) (compose: 0:4) (post: 0:1) (render: 0:5) (0:122 frames) (1:532)
,D/SFPerfTracer(  274):        layers: (0:12) (FocusedStackFrame: 1:8)* (StatusBar: 0:197)* (NavigationBar: 0:37)* (com.android.systemui.ImageWallpaper: 0:7)* (com.android.launcher/com.android.launcher2.Launcher: 0:8)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:10)* (ElectronBeam: 0:27)* 
,D/OpenGLRenderer( 3559): Enabling debug mode 0
,W/AwContents( 3559): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3559): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,421
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +391ms (total +421ms)
,D/JsMessageQueue( 3559): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3559): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4239ee00
,D/dalvikvm( 3559): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4239ee00
D/jxcore_app_log( 3559): JniHelper::setJavaVM(0x41ab3f78), pthread_self() = 1614966288
,D/JX-Cordova( 3559): jxcore cordova android initializing
I/dalvikvm( 3559): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3559): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3559): GC_CONCURRENT freed 2812K, 17% free 14376K/17224K, paused 2ms+2ms, total 65ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 135K, 17% free 14367K/17224K, paused 28ms, total 28ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 131K, 17% free 14387K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.173MB for 95956-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 183K, 17% free 14421K/17320K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.252MB for 143930-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 256K, 18% free 14468K/17464K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.368MB for 215890-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 368K, 18% free 14541K/17676K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 567K, 19% free 14662K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.814MB for 485740-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 865K, 20% free 14837K/18472K, paused 27ms, total 27ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 1281K, 19% free 15094K/18472K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 17.815MB for 1092904-byte allocation
,D/dalvikvm( 3559): GC_CONCURRENT freed 1736K, 21% free 15479K/19540K, paused 3ms+4ms, total 38ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 316K, 22% free 15415K/19540K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 18.650MB for 1639352-byte allocation
,D/dalvikvm( 3559): GC_CONCURRENT freed 1745K, 25% free 16009K/21144K, paused 2ms+6ms, total 46ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 1308K, 25% free 16062K/21144K, paused 32ms, total 32ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 20.063MB for 2459024-byte allocation
,D/dalvikvm( 3559): GC_CONCURRENT freed 209K, 22% free 18403K/23548K, paused 5ms+3ms, total 41ms
,D/dalvikvm( 3559): GC_CONCURRENT freed 4398K, 28% free 17042K/23548K, paused 1ms+7ms, total 54ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 50ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 22.193MB for 3688532-byte allocation
,D/dalvikvm( 3559): GC_CONCURRENT freed 2734K, 34% free 18164K/27152K, paused 2ms+8ms, total 48ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 824K, 34% free 17984K/27152K, paused 30ms, total 31ms
,W/jxcore-log( 3559): Initializing JXcore engine
,W/jxcore-log( 3559): JXcore engine is ready
,D/dalvikvm( 3559): GC_CONCURRENT freed 368K, 25% free 20596K/27152K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 33ms
,W/jxcore-log( 3559): Starting JXcore engine
,W/jxcore-log( 3559): Platform android
W/jxcore-log( 3559): 
,W/jxcore-log( 3559): Process ARCH arm
W/jxcore-log( 3559): 
,I/jxcore-log( 3559): JXcore Cordova bridge is ready!
I/jxcore-log( 3559): 
,W/jxcore-log( 3559): JXcore engine is started
,I/chromium( 3559): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3559): Toggling radios to true
I/jxcore-log( 3559): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1019): Message: 1
,D/BluetoothManagerService( 1019): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1249): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1261): Active network info is not available
I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3606 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
D/WifiService( 1019): setWifiEnabled: true pid=3559, uid=10457
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService( 1019): New client listening to asynchronous messages
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1249): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1249): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1019): setting operational mode to 1
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/jxcore-log( 3559): Radios toggled
I/jxcore-log( 3559): 
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
W/Settings( 1249): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1261): Active network info is not available
,D/AdapterServiceConfig( 3606): Adding HeadsetService
D/AdapterServiceConfig( 3606): Adding A2dpService
D/AdapterServiceConfig( 3606): Adding HidService
D/AdapterServiceConfig( 3606): Adding HealthService
D/AdapterServiceConfig( 3606): Adding PanService
D/AdapterServiceConfig( 3606): Adding GattService
D/AdapterServiceConfig( 3606): Adding BluetoothMapService
,D/BluetoothAdapterService( 3606): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothAdapterState( 3606): make
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4412c430:true
,I/BluetoothAdapterState( 3606): Entering OffState
,I/bluedroid( 3606): init
,I/bte_conf( 3606): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3606): get_profile_interface socket
,I/GKI_LINUX( 3606): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3606): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1019): Message: 40
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
,D/BluetoothAdapterProperties( 3606): Name is: XT1039
,I/bluedroid( 3606): config_hci_snoop_log
,D/BluetoothManagerService( 1019): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3606): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3606): Setting state to 11
I/BluetoothAdapterState( 3606): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3606): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothBondStateMachine( 3606): make
,D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3606): StableState(): Entering Off State
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3635 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1239): Proxy object connected
D/BluetoothHeadset( 1019): Proxy object connected
D/BluetoothHeadset( 1239): Proxy object connected
D/BluetoothHeadset( 1239): Proxy object connected
D/HeadsetService( 3606): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3606): classInitNative: succeeds
D/HeadsetStateMachine( 3606): Version 1.6
D/HeadsetStateMachine( 3606): make
,I/BluetoothAdapterState( 3606): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3606): get_profile_interface handsfree
,D/BluetoothA2dp( 1019): Proxy object connected
D/A2dpService( 3606): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3606): classInitNative: succeeds
,V/Avrcp   ( 3606): make
,I/bluedroid( 3606): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 3606): classInitNative: succeeds
,D/A2dpStateMachine( 3606): make
,I/bluedroid( 3606): get_profile_interface a2dp
,I/GKI_LINUX( 3606): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3606): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3606): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3606): classInitNative: succeeds
D/HidService( 3606): Received start request. Starting profile...
,I/bluedroid( 3606): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3606): classInitNative: succeeds
,D/HealthService( 3606): Received start request. Starting profile...
,I/bluedroid( 3606): get_profile_interface health
,I/BluetoothPanServiceJni( 3606): classInitNative(L105): succeeds
,D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
,D/PanService( 3606): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3606): initializeNative(L110): pan
,I/bluedroid( 3606): get_profile_interface pan
,D/BluetoothTethering( 1019): got CMD_CHANNEL_HALF_CONNECTED
I/BtGatt.JNI( 3606): classInitNative(L684): classInitNative: Success!
,D/BluetoothTethering( 1019): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@440e7550
,D/BtGatt.DebugUtils( 3606): handleDebugAction() action=null
D/BtGatt.GattService( 3606): Received start request. Starting profile...
D/BtGatt.GattService( 3606): start()
,I/bluedroid( 3606): get_profile_interface gatt
,D/BluetoothMapService( 3606): Received start request. Starting profile...
,D/BluetoothMapService( 3606): start()
,D/HeadsetPhoneState( 3606): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 3606): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3606): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3606): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3606): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3606): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3606): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/HeadsetPhoneState( 3606): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3606): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3606): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3606): enable
,I/bt_hci_bdroid( 3606): init
I/bt_vendor( 3606): bt-vendor : init
,I/bt_hci_bdroid( 3606): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3606): userial_init
I/bt_hci_bdroid( 3606): bt_hc_worker_thread started
I/bt_hwcfg( 3606): Starting hciattach daemon
,I/bt_hwcfg( 3606): try to set false
,I/bt_hwcfg( 3606): Starting hciattach daemon
,I/bt_hwcfg( 3606): try to set true
,I/ActivityManager( 1019): Killing 3285:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/qcom-bluetooth( 3668): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
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
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/TCMD    (  457): NL - Read 1004 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1019): InitialState.processMessage what=4
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
,E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  457): NL - Read 1004 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,I/qcom-bluetooth( 3677): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/WifiService( 1019): New client listening to asynchronous messages
D/QsoftapCmd(  270): Got softap fwreload command we are passing on
D/SoftapController(  270): Softap fwReload - Ok
I/qcom-bluetooth( 3679): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring down wlan0
,I/qcom-bluetooth( 3681): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3682): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3683): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,V/BluetoothFtpReceiver( 3606): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
E/Diag_Lib( 3685): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3685): Setting internal use port to rmnet0
E/Diag_Lib( 3685):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3685): Failed on DIAG init
E/Diag_Lib( 3685): linux_qmi_qmux_if_client_get_proc_name: pid=3685, proc_name=hci_qcomm_init
E/Diag_Lib( 3685): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3685): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3685): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3685): qmi_client [3685]: successfully connected to server, attempt=1
E/Diag_Lib( 3685): linux_qmi_qmux_if_client_get_client_id [3685]: qmux_client_id=13
E/Diag_Lib( 3685): qmi_client [3685] 13: qmux_client ID is initialized
E/Diag_Lib( 3685): qmi_client [3685] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3685): qmi_client [3685] 13: sending 880 bytes on fd = 8
,D/WifiStateMachine( 1019): setWifiState: enabling
E/Diag_Lib( 3685): qmi_client [3685] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3685): Sending signal ...... to read cmd data 
E/Diag_Lib( 3685): qmi error code.........:0
E/Diag_Lib( 3685): qmi sys error code.........:0
E/Diag_Lib( 3685): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3685): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3685): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3685): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3685): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3685): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3685): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3685): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3685): qmi_init:  Created client handle b7aaf788
,E/Diag_Lib( 3685): qmi_client [3685] 13: sending 880 bytes on fd = 8
,D/AuthorizationBluetoothService( 1371): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1261): Active network info is not available
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
E/Diag_Lib( 3685): qmi_client [3685] 13: Received 880 bytes on fd = 8
,E/Diag_Lib( 3685): Sending signal ...... to read cmd data 
E/Diag_Lib( 3685): qmi error code.........:0
E/Diag_Lib( 3685): qmi sys error code.........:0
E/Diag_Lib( 3685): Setting the api flag to : 1
,E/Diag_Lib( 3685): qmi_client [3685] 13: sending 54 bytes on fd = 8
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3688): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3688): rfkill: Cannot open RFKILL control device
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,I/rmt_storage(  430): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb839b1d0
I/rmt_storage(  430): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  430): wakelock acquired: 1, error no: 42
,I/rmt_storage(  430): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1204179224)
E/Diag_Lib( 3685): qmi_client [3685] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3685):  API Flag .............. 1 
,E/Diag_Lib( 3685):  Message ID ............... 92 
E/Diag_Lib( 3688): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3688): Setting internal use port to rmnet0
,E/wpa_supplicant( 3688): baseband property is set to [msm]
,E/wpa_supplicant( 3688):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3688): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3688): card_info[i].card_state: 0x2
E/wpa_supplicant( 3688): card_info[i].error_code: 0x3
E/wpa_supplicant( 3688): SIM/USIM not ready
,E/wpa_supplicant( 3688): Error while reading SIM card status
,E/Diag_Lib( 3685): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3685): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3685): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3685): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3685): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3685): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3685): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3685): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3685): qmi_client [3685] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3685): qmi_client [3685] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3685): Sending signal ...... to read cmd data 
E/Diag_Lib( 3685): qmi error code.........:0
E/Diag_Lib( 3685): qmi sys error code.........:0
E/Diag_Lib( 3685): qmi_release: Released client handle ff
E/Diag_Lib( 3685): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3685): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3685): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3685): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3685): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3685): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3685): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3685): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3685): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3685): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3685): qmi_client [3685] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3685): qmi_client [3685] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3685): Sending signal ...... to read cmd data 
E/Diag_Lib( 3685): qmi error code.........:0
E/Diag_Lib( 3685): qmi sys error code.........:0
E/Diag_Lib( 3685): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3685] 13
E/Diag_Lib( 3685): qmi_client [3685] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3685): qmi_client [3685] 13: failed to locate client data
E/Diag_Lib( 3685): qmi_client [3685] 13: calling release of fd=8
,E/Diag_Lib( 3685): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
E/wpa_supplicant( 3688): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3688): card_info[i].card_state: 0x2
E/wpa_supplicant( 3688): card_info[i].error_code: 0x3
E/wpa_supplicant( 3688): SIM/USIM not ready
,I/wpa_supplicant( 3688): eap_proxy: Card not ready
,I/rmt_storage(  430): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  430): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  430): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1204179224) wakelock released: 1, error no: 0
I/rmt_storage(  430): 
,I/rmt_storage(  430): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb839b1d0
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/wpa_supplicant( 3688): Long line in configuration file truncated
,I/wpa_supplicant( 3688): rfkill: Cannot open RFKILL control device
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,I/qcom-bluetooth( 3691): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3692): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3606): bluetooth satus is on
D/bt_userial_mct( 3606): userial_open(port:0)
I/GKI_LINUX( 3606): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3606): btu_task pending for preload complete event
,I/bt_userial_vendor( 3606): Done intiailizing UART
I/bt_userial_vendor( 3606): Done intiailizing UART
I/bt_userial_mct( 3606): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3606): Bluetooth Firmware and smd is initialized
,D/bt_userial_mct( 3606): Entering userial_read_thread()
,I/bt-btu  ( 3606): btu_task received preload complete event
,I/        ( 3606): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3606): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3606): BTE_InitTraceLevels -- TRC_RFCOMM
,I/        ( 3606): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3606): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3606): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3606): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3606): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 3606): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3606): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3606): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3606): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3606): BTE_InitTraceLevels -- TRC_SMP
,I/        ( 3606): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3606): BTE_InitTraceLevels -- TRC_BTIF
,E/wpa_supplicant( 3688): COUNTRY Code Recived
,E/wpa_supplicant( 3688): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3688): baseband property is set to [msm]
,E/wpa_supplicant( 3688):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3688): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3688): card_info[i].card_state: 0x2
E/wpa_supplicant( 3688): card_info[i].error_code: 0x3
E/wpa_supplicant( 3688): SIM/USIM not ready
,E/wpa_supplicant( 3688): Error while reading SIM card status
E/wpa_supplicant( 3688): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3688): card_info[i].card_state: 0x2
E/wpa_supplicant( 3688): card_info[i].error_code: 0x3
E/wpa_supplicant( 3688): SIM/USIM not ready
,I/wpa_supplicant( 3688): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
E/bt-btm  ( 3606): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f100049 
,E/bt-btm  ( 3606): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f100049 
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,E/bt-btif ( 3606): Calling BTA_HhEnable
E/bt-btif ( 3606): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3606): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:1 len:6
,W/XTWiFiOS( 1261): Active network info is not available
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/BluetoothAdapterProperties( 3606): Name is: XT1039
D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
,I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3688): COUNTRY Code Recived -COUNTRY PL
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
D/BluetoothAdapterProperties( 3606): Scan Mode:21
,I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3606): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:8 len:0
,I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:3 len:48
,I/bte_conf( 3606): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
E/bt_mct  ( 3606): hci lib postload completed
,I/bte_conf( 3606): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3606): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3606): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothPanServiceJni( 3606): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,D/BluetoothAdapterState( 3606): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3606): ScanMode =  21
D/BluetoothAdapterProperties( 3606): State =  11
,D/BluetoothAdapterProperties( 3606): Setting state to 12
I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:9 len:4
I/BluetoothAdapterState( 3606): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3606): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService( 1019): Message: 60
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan( 1019): onBluetoothStateChange on: true
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3606): Entering On State
,D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 3606): Discoverable Timeout:120
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothAdapterService(1111103072)( 3606): Get Bonded Devices being called
D/BluetoothAdapterService(1111103072)( 3606): Get Bonded Devices being called
,D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService( 1019): Message: 40
,D/BluetoothMapService( 3606): onReceive
D/BluetoothMapService( 3606): STATE_ON
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3606): Map Service startRfcommSocketListener
,D/BluetoothAdapterService(1111103072)( 3606): Get Bonded Devices being called
,D/WifiStateMachine( 1019): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3688): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3688): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/BluetoothMapService( 3606): Map Service initSocket
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3606): getBluetoothService() called with no BluetoothManagerCallback
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,E/BluetoothServiceJni( 3606): SOCK FLAG = 1 ***********************
,I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:7 len:4
I/qcom-bt-wlan-coex( 3706): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothAdapterProperties( 3606): Scan Mode:21
,D/BluetoothMapService( 3606): Accepting socket connection...
,D/WifiP2pService( 1019): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  270): Setting iface cfg
D/CommandListener(  270): Trying to bring up p2p0
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
D/WifiStateMachine( 1019): handleMessage: X
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
E/wpa_supplicant( 3688): COUNTRY Code Recived
E/wpa_supplicant( 3688): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set frequency band 2
,W/ContextImpl( 3635): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/wpa_supplicant( 3688): wlan0: Failed to initiate AP scan
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
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
,D/WifiP2pService( 1019): MCC mode enabled 0
,D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
,D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
,D/WifiP2pService( 1019): InactiveState{ when=-23ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-23ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): InactiveState{ when=-24ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-24ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3688): COUNTRY Code Recived
D/BluetoothPbapService( 3606): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothPbapService( 3606): Handler(): got msg=1
,E/wpa_supplicant( 3688): COUNTRY Code Recived
D/WifiP2pService( 1019): InactiveState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-9ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3606): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@440b1778:true
,D/LocalBluetoothProfileManager( 3635): Adding local A2DP profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3635): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3635): Adding local HEADSET profile
E/BluetoothServiceJni( 3606): SOCK FLAG = 1 ***********************
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3635): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1019): Message: 30
W/ContextImpl( 3635): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/dalvikvm( 1019): GC_EXPLICIT freed 22628K, 65% free 17854K/50280K, paused 4ms+10ms, total 145ms
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3635): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3635): Adding local MAP profile
D/BluetoothMap( 3635): Create BluetoothMap proxy object
D/BluetoothManagerService( 1019): Message: 30
D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/ContextImpl( 3635): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3635): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3635): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3635): finishStartingService: stopping service
,D/BluetoothAdapterService(1111103072)( 3606): Get Bonded Devices being called
,D/BluetoothA2dp( 3635): Proxy object connected
,D/A2dpProfile( 3635): Bluetooth service connected
,D/BluetoothHeadset( 3635): Proxy object connected
,D/HeadsetProfile( 3635): Bluetooth service connected
,D/BluetoothInputDevice( 3635): Proxy object connected
,D/HidProfile( 3635): Bluetooth service connected
,D/BluetoothPan( 3635): BluetoothPAN Proxy object connected
D/PanProfile( 3635): Bluetooth service connected
D/BluetoothMap( 3635): Proxy object connected
D/MapProfile( 3635): Bluetooth service connected
,D/BluetoothMap( 3635): getConnectedDevices()
,D/BluetoothPbap( 3635): Proxy object connected
,D/PbapServerProfile( 3635): Bluetooth service connected
,V/BluetoothFtpReceiver( 3606): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3606): BluetoothFtpReceiver Start Service
D/AuthorizationBluetoothService( 1371): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1371): Proximity feature is not enabled.
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3606): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3606): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3606): Accept thread started.
V/BluetoothFtpService( 3606): Ftp Service onCreate
I/BluetoothFtpService( 3606): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3606): Starting FTP service
,V/BluetoothFtpService( 3606): Ftp Service onStartCommand
,V/BluetoothFtpService( 3606): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3606): Handler(): got msg=1
V/BluetoothFtpService( 3606): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3606): Ftp Service initSocket
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3606): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3606): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3606): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3606): Run Accept thread
,D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  273): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): wifi_connect_to_supplicant, current pid is = 273
D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  273): wifi_close_sockets: Exit
,E/MDMCTBK (  273): Attach monitor thread
I/MDMCTBK (  273): createWifiMonitorThread: Started the wifi monitor thread -1222572864
,D/MDMCTBK (  273): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/wpa_supplicant( 3688): wlan0: Failed to initiate AP scan
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  273): Event received = Failed to initiate AP scan
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,I/wpa_supplicant( 3688): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c2:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c0:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 06:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 06:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 64:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 64:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 fc:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 fc:
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  457): NL - Read 56 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
I/wpa_supplicant( 3687): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3687): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,E/wpa_supplicant( 3688): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 3688): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 3688): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  457): NL - Read 312 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 192 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,I/wpa_supplicant( 3688): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  457): NL - Read 80 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 80 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3688): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
I/wpa_supplicant( 3688): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  273):  STA Connected !!
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
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
,I/MDMCTBK (  273): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
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
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1222576968
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
,D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-53ms what=147462 obj=android.net.wifi.StateChangeResult@423da428 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-31ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4270bde8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42be1b80 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42be1b80 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 f
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 f
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 fc
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  457): NL - Read 56 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42be7920 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42be7920 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42be7920 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  457): NL - Read 60 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 20
,D/TCMD    (  457): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
,D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1019): WiFi NOT Tethered!
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4246f050
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1277): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1277): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1277): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@4246f050
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1277): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1277): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1277): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        ( 1019): Setting time of day to sec=1449746484
,W/        ( 1019): Unable to set rtc to 1449746484: Invalid argument
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3793 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/PollingManager( 1539): now: 354026 ,futureTime: 11781622
,D/PollingManager( 1539): Polling alarm set to expire at: 11781622 Current Time: 354027
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1539): registerApp(): CCE
I/CCE     ( 1539): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1539): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1539): now: 354084 ,futureTime: 11781622
,D/PollingManager( 1539): Polling alarm set to expire at: 11781622 Current Time: 354084
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/MMApiWebService( 1539): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1539): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1539): isRequestAllowed(): already have outstanding request ... ignoring request
D/CCE     ( 1539): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1539): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1539): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1539): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1539): generating token using payload instead of using session token
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1539): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1539): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1539): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1539): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1202): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1202): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1202): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1202): Using platform SSLCertificateSocketFactory
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1019): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3828 uid=10056 gids={50056, 3003, 1028, 1015}
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 3793): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4239a298, skipping init
I/openssl ( 3793): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3793): Crypto mode 0 already enabled
I/PhenotypeConfigurator( 1202): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3853 uid=10030 gids={50030, 3003, 1028, 1015}
V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1019): Killing 3405:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 3853): mnc/mcc: 
V/MmsConfig( 3853): tag: bool value: enabledMMS - true
,V/MmsConfig( 3853): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3853): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3853): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3853): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3853): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3853): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3853): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 3853): tag: int value: recipientLimit - 20
V/MmsConfig( 3853): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3853): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3853): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3853): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 3853): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3853): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3853): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3853): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3853): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/dalvikvm( 1385): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1385): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1385): VFY: replacing opcode 0x6e at 0x003d
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/DelayedSyncController( 3828): Delaying sync.
I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3876 uid=10041 gids={50041, 3003}
I/ActivityManager( 1019): Killing 3068:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
E/ActivityThread( 1385): Failed to find provider info for com.android.contacts.metadata
,D/GpsLocationProvider( 1019): NTP server returned: 1449746481764 (Thu Dec 10 12:21:21 CET 2015) reference: 351003 certainty: 11 system time offset: -3522
,E/Auth.Api.Credentials( 1385): [CredentialSyncAdapter] Unknown sync event.
,E/LocSvc_ApiV02( 1019): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,I/dalvikvm( 1202): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1202): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1202): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1239): GC_EXPLICIT freed 1460K, 45% free 9517K/17224K, paused 21ms+5ms, total 76ms
,D/MobileConnectivityChangeReceiver( 3876): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3876): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3876): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3876): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1019): Killing 3436:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3896 uid=10076 gids={50076, 3003, 1028, 1015}
,D/dalvikvm( 1385): GC_CONCURRENT freed 1798K, 31% free 11894K/17224K, paused 6ms+5ms, total 67ms
,I/ActivityManager( 1019): Killing 3084:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/SyncManager( 1019): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 354660, reason: UserStart
,D/dalvikvm( 1019): GC_EXPLICIT freed 1642K, 65% free 17914K/50280K, paused 5ms+11ms, total 110ms
,I/CheckinService( 1385): Checkin interval check for package: unspecified last checkin: 1449704377349 min interval config: 0 actual interval: 42108137
,I/CheckinService( 1385): Checking schedule, now: 1449746485501 next: 1449704407305
,I/CheckinService( 1385): active receiver: enabled
,I/CheckinService( 1385): Preparing to send checkin request
,I/EventLogService( 1385): Accumulating logs since 1449746163265
,I/CheckinRequestBuilder( 1385): Checkin reason type: 8 attempt count: 1
,V/WebViewChromiumFactoryProvider( 3896): Binding Chromium to main looper Looper (main, tid 1) {42396ff0}
,I/LibraryLoader( 3896): Expected native library version number "",actual native library version number ""
,I/chromium( 3896): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3896): Initializing chromium process, renderers=0
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/WifiService( 1019): New client listening to asynchronous messages
,E/ActivityThread( 1385): Failed to find provider info for com.google.android.wearable.settings
D/dalvikvm( 1371): GC_CONCURRENT freed 1889K, 41% free 10306K/17224K, paused 3ms+4ms, total 34ms
E/AudioManagerAndroid( 3896): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3896): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3896): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3896): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3896): Local Branch: 
I/Adreno-EGL( 3896): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3896): Local Patches: NONE
I/Adreno-EGL( 3896): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
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
,W/chromium( 3896): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3896): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/DelayedSyncController( 3828): Delaying sync.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3896): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/dalvikvm( 1202): GC_EXPLICIT freed 1463K, 35% free 11297K/17224K, paused 14ms+11ms, total 92ms
,D/MMApiWSBase( 1539): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1539): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,I/NSApplication( 3896): Starting up...
,D/CCE     ( 1539): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/dalvikvm( 1385): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1385): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1385): VFY: replacing opcode 0x71 at 0x004e
,I/ImageResourceManager( 3101): ImageResourceManager: uninitalized
,I/iu.Environment( 3101): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3101): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 3461:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3101): num queued entries: 0
,I/iu.UploadsManager( 3101): num updated entries: 0
D/Checkin ( 1539): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,I/iu.SyncManager( 3101): NEXT; no task
,D/SundryService( 1539): handleGetNotificationsResponse(): got 0; more=false
,D/dalvikvm( 1385): DexOpt: --- BEGIN 'ads2060361512.jar' (bootstrap=0) ---
,I/iu.SyncManager( 1385): SYNC; picasa accounts
,D/NetworkLogImpl( 1385): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1385): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/openssl ( 3793): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3793): Crypto mode 0 already enabled
,I/iu.UploadsManager( 1385): num queued entries: 0
,D/MobileConnectivityChangeReceiver( 3876): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3876): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.UploadsManager( 1385): num updated entries: 0
,I/iu.SyncManager( 1385): NEXT; no task
,I/iu.Environment( 3101): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3961 uid=10007 gids={50007, 3003}
,D/dalvikvm( 3101): GC_CONCURRENT freed 617K, 5% free 16454K/17224K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 3954): DexOpt: load 8ms, verify+opt 14ms, 192820 bytes
,D/MMApiProvisionService( 1539): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"97802","deviceId":"1135300315450105856"}
,D/dalvikvm( 1385): DexOpt: --- END 'ads2060361512.jar' (success) ---
,D/dalvikvm( 1385): DEX prep '/data/data/com.google.android.gms/cache/ads2060361512.jar': unzip in 0ms, rewrite 185ms
,D/MMApiProvisionService( 1539): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3973 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
D/MMApiWSBase( 1539): doRequest(): /v1/dp/devices.json resp length: 137
D/MMApiProvisionService( 1539): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1539): handleResponse(): Session Expiration alarm set to expire at: Fri Dec 11 15:31:28 CET 2015
,D/MMApiProvisionService( 1539): _setMMApiCredInfo: storing credential info 
,W/dalvikvm( 3973): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3973): VFY: replacing opcode 0x60 at 0x000b
,E/MMApiProvisionService( 1539): handleResponse(): no settings sent by the server:
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/dalvikvm( 3973): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3973): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3973): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 3973): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3973): install
,D/MMApiWebService( 1539): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,I/MultiDex( 3973): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 3973): loading existing secondary dex files
,I/MultiDex( 3973): load found 3 secondary dex files
,I/MultiDex( 3973): install done
,D/ExtensionsFactory( 3961): No custom extensions.
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3993 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 3120:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/GCM     ( 1371): GCM config loaded
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4007 uid=10008 gids={50008, 3003, 1028, 1015}
,D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
I/ActivityManager( 1019): Killing 3635:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 3973): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3973): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3973): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3973): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3973): VFY: unable to resolve instance field 36
D/dalvikvm( 3973): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3973): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3973): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 3973): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
D/dalvikvm( 3973): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3973): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 3973): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4239dc68
D/dalvikvm( 3973): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4239dc68
D/dalvikvm( 3973): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4239dc68, skipping init
D/dalvikvm( 3973): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4239dc68
D/dalvikvm( 3973): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4239dc68
V/JNIHelp ( 3973): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/WifiService( 1019): Client connection lost with reason: 4
I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,V/AlarmClock( 3993): AlarmInitReceiver android.intent.action.TIME_SET
,I/CalendarProvider2( 4007): Created com.android.providers.calendar.CalendarAlarmManager@423b3f08(com.android.providers.calendar.CalendarProvider2@423abac0)
,I/AlarmClock( 3993): Displaying next alarm time: ''
,W/PhenotypeConfigurator( 1202): Server returned 404
D/dalvikvm( 3973): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4239dc68
,D/dalvikvm( 3973): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4239dc68
D/dalvikvm( 3973): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4239dc68
,D/dalvikvm( 3973): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4239dc68
,V/AlarmClock( 3993): AlarmInitReceiver finished
,I/ActivityManager( 1019): Killing 3793:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4026 uid=10098 gids={50098}
,D/dalvikvm( 4026): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42394e30, skipping init
,D/TimeService( 4026): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449746486611
D/        ( 4026): TimeServiceNative: User Time to be set is 1449746486611
D/QC-time-services( 4026): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4026): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4026): Lib:time_genoff_operation: pargs->ts_val = 1449746486611
D/QC-time-services( 4026): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  415): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  415): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449746486611
D/QC-time-services(  415): Daemon:genoff_opr: Base = 2, val = 1449746486611, operation = 0
D/QC-time-services(  415): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/10/115 11:15:32
D/QC-time-services(  415): Daemon:Value read from RTC seconds = 1449746132000
D/QC-time-services(  415): Daemon:new time 1449746486611 
D/QC-time-services(  415): Daemon: delta 354611 genoff 354611 
,D/QC-time-services(  415): Daemon:genoff_persistent_update: Writing genoff = 354611 to memory
D/QC-time-services(  415): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  415): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  415): Updating the TOD offset
D/QC-time-services(  415): Daemon:genoff_persistent_update: Writing genoff = 354611 to memory
D/QC-time-services(  415): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  415): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  415): Daemon:Update to modem bit set
D/QC-time-services(  415): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  415): Daemon: Base = 2, Value being sent to MODEM = 18446743757745106227
,E/QC-time-services( 4026): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  415): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  415): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1385): Checkin interval check for package: unspecified last checkin: 1449704377349 min interval config: 0 actual interval: 42109285
,I/ProviderInstaller( 3973): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 3973): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 3973): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 3973): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 3973): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 3973): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3973): VFY: replacing opcode 0x6e at 0x000d
,D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
,D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
I/dalvikvm( 3973): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3973): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 3973): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 3973): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 3973): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3973): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 3973): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3973): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 3973): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3973): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 3973): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/OtaApp  ( 1539): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1539): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1539
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1539): GC_CONCURRENT freed 2215K, 38% free 10812K/17224K, paused 9ms+3ms, total 60ms
,D/OtaApp  ( 1539): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1539): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1539
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,159
D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/WVCdm   (  277): Instantiating CDM.
I/WVCdm   (  277): Level3 Library Nov 20 2013 18:09:31
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{4248b1b8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
D/DEBUG   ( 1539): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1539): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1539): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
D/DEBUG   ( 1539): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1539): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1539): bindWebServices(): registering our AIDL callback...
D/DrmWidevineDash(  277): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  277): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  277): App is not loaded in QSEE
E/QSEECOMAPI: (  277): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  277): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  277): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  277): App is not loaded in QSEE
E/QSEECOMAPI: (  277): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  277): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  277): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  277): App is not loaded in QSEE
D/GetNotificationsWS( 1539): onServiceConnected()
,D/GetNotificationsWS( 1539): onServiceConnected(): Registered for remote service callbacks...
I/SundryService( 1539): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1539): Received shoulder tap
,D/WearableService( 1202): callingUid 10022, callindPid: 1202
,D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,I/dalvikvm( 3973): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 3973): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3973): VFY: replacing opcode 0x6e at 0x003d
,D/GetNotificationsWS( 1539): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1539): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=1
,D/QSEECOMAPI: (  277): Loaded image: APP id = 3
,D/DrmWidevineDash(  277): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb516a000
,E/DrmWidevineDash(  277): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb516a000
,D/NativeLibraryUtils( 3973): Install completed successfully. count=14 extracted=0
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1277): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1277): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1277): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1277): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/DrmWidevineDash(  277): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  277): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  277): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  277): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  277): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=1608021092
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 1019): GC_EXPLICIT freed 810K, 65% free 17924K/50280K, paused 5ms+15ms, total 132ms
,D/LocationInitializer( 1385): Restart initialization of location
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/AuthorizationBluetoothService( 1371): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1371): Proximity feature is not enabled.
,E/MDM     ( 1202): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/dalvikvm( 3973): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 3973): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3973): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 3973): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 3973): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 3973): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 3973): Using platform SSLCertificateSocketFactory
,W/GCoreFlp( 1202): No location to return for getLastLocation()
,W/FusedLocationProvider( 1202): location=null
,I/MMApiWSBase( 1539): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,I/CalendarProvider2( 4007): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4007): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3961): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3961): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 3973): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4275d788
,D/dalvikvm( 3973): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4275d788
,D/dalvikvm( 3973): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x4275d788, skipping init
,D/MMApiWSBase( 1539): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1539): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1539): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1539): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1539): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1539): Received intent : com.motorola.ccc.notification.action.NOTIFY
,I/SundryService( 1539): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1539): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1539): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,I/PhenotypeConfigurator( 1202): Scheduling Phenotype for one-off execution 13687 seconds from now (1449746487899)
,D/GetConfigurationSnapshotOperation( 1202): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,W/Settings( 3973): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/DrmWidevineDash(  277): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  277): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  277): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  277): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  277): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  277): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  277): PrepareKeyRequest: nonce=3128731491
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  277): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/PhenotypeFlagCommitter( 1202): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1202): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1202): GC_CONCURRENT freed 1640K, 33% free 11582K/17224K, paused 5ms+12ms, total 46ms
,D/DrmWidevineDash(  277): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  277): CdmEngine::CloseSession
,D/DrmWidevineDash(  277): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  277): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 3973): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4072): DexOpt: load 4ms, verify+opt 6ms, 128132 bytes
,D/dalvikvm( 3973): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3973): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 85ms
,I/Adreno-EGL( 3973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3973): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3973): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3973): Local Branch: 
I/Adreno-EGL( 3973): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3973): Local Patches: NONE
I/Adreno-EGL( 3973): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1385): GC_CONCURRENT freed 1816K, 30% free 12086K/17224K, paused 4ms+8ms, total 50ms
,I/Adreno-EGL( 3973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3973): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3973): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3973): Local Branch: 
I/Adreno-EGL( 3973): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3973): Local Patches: NONE
I/Adreno-EGL( 3973): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3973): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3973): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3973): Local Branch: 
I/Adreno-EGL( 3973): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3973): Local Patches: NONE
I/Adreno-EGL( 3973): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3973): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3973): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3973): Local Branch: 
I/Adreno-EGL( 3973): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3973): Local Patches: NONE
I/Adreno-EGL( 3973): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1385): Classify the device as Phone.
,I/jxcore-log( 3559): Test app app.js loaded
I/jxcore-log( 3559): 
,W/IInputConnectionWrapper( 3559): showStatusIcon on inactive InputConnection
,I/CheckinTask( 1385): Sending checkin request (11868 bytes)
,I/chromium( 3559): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/CheckinResponseProcessor( 1385): From server: 1 gservices updates and 1 deletes
,D/dalvikvm( 1371): GC_EXPLICIT freed 1262K, 40% free 10363K/17224K, paused 4ms+7ms, total 65ms
,E/UlpEngine( 1019): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,E/UlpEngine( 1019): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
I/CertBlacklister( 1019): Certificate blacklist changed, updating...
I/CertBlacklister( 1019): Certificate blacklist updated
,I/GservicesProvider( 1371): main difference update completed
,I/ActivityManager( 1019): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4103 uid=10009 gids={50009, 3003, 2001}
,I/CheckinRequestBuilder( 1385): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1385): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4103): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4103): Update started
,E/UpdateRequestReceiver( 4103): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4131 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,W/ContextImpl( 4103): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4103): Update started
,E/UpdateRequestReceiver( 4103): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4103): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4103): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager( 1019): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4153 uid=10025 gids={50025, 3003}
,I/CheckinRequestBuilder( 1385): Classify the device as Phone.
,D/dalvikvm( 4131): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x423992f8, skipping init
I/openssl ( 4131): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4131): Crypto mode 0 already enabled
,I/CheckinTask( 1385): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/ContactAccountLoggerTas( 2130): canRun() : Opted Out
,I/Search.GservicesUpdateTask( 2130): Updating Gservices keys
I/CheckinService( 1385): Checking schedule, now: 1449746490533 next: 1450339560497
,I/CheckinService( 1385): active receiver: disabled
,D/CheckinService( 1385): Recording last checkin time for package unspecified as 1449746490574
,I/DownloadManager( 4131): Download 263 starting
,I/DownloadManager( 4131): Download 262 starting
,W/ActivityThread( 4131): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ContactAccountLoggerTas( 2130): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2130): canRun() : Opted Out
,I/ActivityManager( 1019): Killing 3853:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1385): Checkin interval check for package: unspecified last checkin: 1449746490574 min interval config: 0 actual interval: 174
,D/dalvikvm( 3101): GC_FOR_ALLOC freed 165K, 5% free 16523K/17224K, paused 39ms, total 39ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 833K, 65% free 17762K/50280K, paused 4ms+10ms, total 106ms
,D/dalvikvm( 1385): GC_CONCURRENT freed 2002K, 31% free 12023K/17224K, paused 3ms+5ms, total 57ms
,W/SQLiteConnectionPool( 1385): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ContactAccountLoggerTas( 2130): canRun() : Opted Out
,I/ActivityManager( 1019): Killing 3828:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/GAV2    ( 3896): Thread[GAThread,5,main]: No campaign data found.
I/SystemUpdateService( 1385): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/SystemUpdateService( 1385): onCreate
D/SystemUpdateService( 1385): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/CheckinService( 1385): Checking schedule, now: 1449746490821 next: 1450339560497
I/CheckinService( 1385): active receiver: disabled
,D/dalvikvm( 3101): GC_FOR_ALLOC freed 13K, 4% free 18313K/19004K, paused 12ms, total 12ms
I/SystemUpdateService( 1385): cancelUpdate (empty URL)
I/SystemUpdateService( 1385): active receiver: disabled
,D/dalvikvm( 1371): GC_EXPLICIT freed 940K, 40% free 10381K/17224K, paused 2ms+4ms, total 35ms
,D/dalvikvm( 1371): null clazz in OP_INSTANCE_OF, single-stepping
,I/DownloadManager( 4131): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1371): GC_EXPLICIT freed 118K, 40% free 10358K/17224K, paused 2ms+4ms, total 31ms
,D/Checkin ( 4131): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/Auth    ( 1371): [BroadcastManager] Broadcasting account services changed.
,I/DownloadManager( 4131): Download 263 finished with status SUCCESS
,D/SystemUpdateService( 1385): onDestroy
,E/DynamiteModule( 1385): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1385): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1385): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1385): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1385): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1385): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1385): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1385): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1385): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1385): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1385): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1385): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/DynamiteModule( 1385): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/DynamiteModule( 1385): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/DynamiteModule( 1385): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1385): 	at android.os.Looper.loop(Looper.java:136)
E/DynamiteModule( 1385): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/DynamiteModule( 1385): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1385): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1385): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/DynamiteModule( 1385): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/DynamiteModule( 1385): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1385): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1385): Selected local version of com.google.android.gms.flags
I/DownloadManager( 4131): Ignoring Content-Length since Transfer-Encoding is also defined
,D/Checkin ( 4131): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4131): Download 262 finished with status SUCCESS
,D/dalvikvm( 1385): GC_EXPLICIT freed 529K, 30% free 12061K/17224K, paused 4ms+6ms, total 46ms
I/ActivityManager( 1019): Killing 3896:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/SystemEventReceiver( 1385): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1385): Updating ocr activity enabled=false
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1385): Updating downloaded model state (gservices changed)
,D/GCM     ( 1371): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/Auth    ( 1371): [BroadcastManager] Broadcasting account services changed.
,E/dalvikvm( 1202): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
W/dalvikvm( 1202): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/dalvikvm( 1202): VFY: replacing opcode 0x1f at 0x001a
,D/dalvikvm( 1202): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm( 1202): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
W/dalvikvm( 1202): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1202): VFY: replacing opcode 0x6e at 0x0012
,D/dalvikvm( 1202): GC_CONCURRENT freed 1959K, 33% free 11619K/17224K, paused 3ms+7ms, total 39ms
,D/dalvikvm( 1371): GC_EXPLICIT freed 472K, 40% free 10430K/17224K, paused 2ms+4ms, total 28ms
,I/GCoreUlr( 1202): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1202): DispatchingService.onCreate()
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1202): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ContextImpl( 4103): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
,I/openssl ( 4131): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4131): Crypto mode 0 already enabled
,E/ctxmgr  ( 1202): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,W/ContextImpl( 4103): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,W/ctxmgr  ( 1202): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10022, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,I/DownloadManager( 4131): Download 264 starting
,E/ctxmgr  ( 1202): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/DownloadManager( 4131): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 4131): Download 265 starting
,I/GCoreUlr( 1202): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1202): Unbound from all location providers
,I/GCoreUlr( 1202): Place inference reporting - stopped
,I/DownloadManager( 4131): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1019): GC_EXPLICIT freed 760K, 65% free 17802K/50280K, paused 4ms+11ms, total 99ms
,D/Checkin ( 4131): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,D/Checkin ( 4131): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/GCoreUlr( 1202): DispatchingService.onDestroy()
,I/GCoreUlr( 1202): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1202): Unbound from all location providers
,I/GCoreUlr( 1202): Place inference reporting - stopped
,I/DownloadManager( 4131): Download 265 finished with status SUCCESS
,I/DownloadManager( 4131): Download 264 finished with status SUCCESS
,W/ContextImpl( 4103): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4103): Update downloaded, starting installation
,I/UpdateFetcherService( 4103): Started installation
,I/openssl ( 4131): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4131): Crypto mode 0 already enabled
,W/ContextImpl( 4103): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/ContactAccountLoggerTas( 2130): canRun() : Opted Out
,I/UpdateFetcherService( 4103): Update downloaded, starting installation
,I/UpdateFetcherService( 4103): Started installation
,I/ConfigUpdateInstallReceiver( 1019): Not installing, new version is <= current version
,I/GlobalDismissManager( 3961): no sender configured
,D/AlertService( 3961): Beginning updateAlertNotification
,D/AlertService( 3961): No fired or scheduled alerts
,D/AlertService( 3961): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3961): No events found starting within 1 week.
I/ActivityManager( 1019): Killing 4007:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 4026:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.174/generate_204
W/ActivityThread( 1019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4263 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/Launcher( 1294): Deferring update until onResume
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/Launcher( 1294): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/GAV2    ( 3101): Thread[GAThread,5,main]: No campaign data found.
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
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Babel   ( 4263): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4263): MmsConfig.loadMmsSettings
I/Babel   ( 4263): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4263): MmsConfig.loadFromDatabase
,I/GCoreNlp( 1202): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
E/Babel   ( 4263): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4263): MmsConfig.loadFromResources
,E/Babel   ( 4263): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4263): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4263): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4304 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 3993:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4323 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3961:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2130): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4340 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4153:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4304): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4340): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4340): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x000e
,I/InternalIcingCorporaPro( 2130): UpdateCorporaTask done [took 222 ms] updated apps [took 222 ms] 
,D/Finsky  ( 4340): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4340): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4340): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4340): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4340): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4340): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4340): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4340): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4340): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4340): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4340): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4340): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4340): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4340): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4340): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4340): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4340): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4340): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x0019
,D/dalvikvm( 1371): GC_EXPLICIT freed 420K, 40% free 10391K/17224K, paused 2ms+4ms, total 27ms
,D/Finsky  ( 4340): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4340): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4340): Skipping gmscore version check
,D/Finsky  ( 4340): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4340): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4340): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4340): VFY: replacing opcode 0x6e at 0x0017
,D/PackageBroadcastService( 1385): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1385): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 4340): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1385): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager( 1019): Killing 3876:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1202): GC_EXPLICIT freed 1042K, 34% free 11517K/17224K, paused 3ms+5ms, total 38ms
,I/Icing   ( 1385): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/Icing   ( 1385): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1385): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449746497
,W/PackageSettings( 1019): Skipping PackageSetting{42656320 com.example.hello/10442} due to missing metadata
,D/dalvikvm( 1019): GC_CONCURRENT freed 1837K, 65% free 18080K/50280K, paused 9ms+9ms, total 96ms
,V/AlarmManager( 1019): sending alarm Alarm{44b064f0 type 2 android}
,I/dalvikvm( 1385): Jit: resizing JitTable from 4096 to 8192
,V/AlarmManager( 1019): sending alarm Alarm{44ac3118 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{44ba7950 type 2 android}
,E/ActivityThread( 1385): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 1019): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 414586, reason: UserStart
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3559): Toggling radios to false
I/jxcore-log( 3559): 
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@441270b0 mBinding = false
,W/Settings( 1249): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/BluetoothManagerService( 1019): Message: 2
D/BluetoothManagerService( 1019): Sending off request.
D/BluetoothAdapterState( 3606): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3606): Setting state to 13
I/BluetoothAdapterState( 3606): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3606): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 3606): onBluetoothDisable()
I/BluetoothAdapterState( 3606): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 3606): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3606): Scan Mode:21
D/BluetoothAdapterState( 3606): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService( 1019): Message: 60
E/bt-btif ( 3606): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 3606): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3606): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
E/bt-btif ( 3606): bta_jv_rfcomm_stop_server
E/bt-btif ( 3606): bta_jv_rfcomm_stop_server
E/bt-btif ( 3606): bta_jv_rfcomm_stop_server
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 12 -> 13
W/bt-btif ( 3606): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3606): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3606): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 3606): onReceive
,D/BluetoothMapService( 3606): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 3606): MAP Service closeService in
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4424 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/btif_config_util( 3606): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/Settings( 1249): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1019): setWifiEnabled: false pid=3559, uid=10457
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,I/BtOppRfcommListener( 3606): stopping Accept Thread
,I/BtOppRfcommListener( 3606): BluetoothSocket listen thread finished
,W/Settings( 1249): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
I/jxcore-log( 3559): Radios toggled
I/jxcore-log( 3559): 
W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,W/Settings( 1249): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  270): Clearing all IP addresses on wlan0
D/TCMD    (  457): NL - Read 60 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 21
,D/TCMD    (  457): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 90856
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x616d8190 clazz=0x64600001 iface=wlan0 mask=0x3
,D/WifiP2pService( 1019): P2pDisablingState
D/WifiP2pService( 1019): P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,V/NativeCrypto( 1371): Read error: ssl=0x62c2ee68: I/O error during system call, Connection timed out
D/WifiP2pService( 1019): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1371): SSL shutdown failed: ssl=0x62c2ee68: I/O error during system call, Broken pipe
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiStateMachine( 1019): stopping supplicant
I/bt_hwcfg( 3606): hw_epilog_process
W/bt-btif ( 3606): ag scb idx 1 not allocated
E/bt-btif ( 3606): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3606): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3606): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3606): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3606): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3606): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3606): L2CAP - PSM: 0x0017 not found for deregistration
D/WifiStateMachine( 1019): setWifiState: disabling
D/WifiStateMachine( 1019): handleMessage: X
W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1261): Active network info is not available
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
E/XTCC-3.0.0.2(  610): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  610): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/XTCC-3.0.0.2(  610): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  610): [CSMgr] handleConnectivtyStatusChange failed
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/bt_hwcfg( 3606): hw_epilog_cback Opcode:0x0C03 Status: 0
I/ModemStatsDSDetect( 1277): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/bt_hci_bdroid( 3606): bt_hc_worker_thread exiting
D/bt_userial_mct( 3606): userial_close
I/bt_userial_mct( 3606): exiting userial_read_thread
,D/bt_userial_mct( 3606): Leaving userial_evt_read_thread()
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1277): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1277): onReceive() - done, currentInetCondition=0
,W/ContextImpl( 4424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothPbapService( 3606): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@434fb790:true
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4424): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4424): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 4424): Adding local MAP profile
D/BluetoothMap( 4424): Create BluetoothMap proxy object
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4424): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
I/ModemStatsDSDetect( 1277): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1277): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1277): onReceive() - done, currentInetCondition=0
I/wpa_supplicant( 3688): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  273): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  273):  STA Disconnected !!
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): get_property_value, Enter
I/MDMCTBK (  273): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  273): get_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
D/TCMD    (  457): NL - Read 68 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/BluetoothManagerService( 1019): Message: 30
D/Tethering( 1019): InitialState.processMessage what=4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
W/ContextImpl( 4424): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4424): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 4424): finishStartingService: stopping service
,D/WifiService( 1019): New client listening to asynchronous messages
I/wpa_supplicant( 3688): eap_proxy Deinitialzed
D/BTSNOOP-DISP( 3606): btsnoop_close
I/bt_vendor( 3606): cleanup
I/bt_hwcfg( 3606): Starting hciattach daemon
I/bt_hwcfg( 3606): try to set false
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7
I/GKI_LINUX( 3606): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3606): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 3606): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/BluetoothInputDevice( 4424): Proxy object connected
D/HidProfile( 4424): Bluetooth service connected
D/BluetoothPan( 4424): BluetoothPAN Proxy object connected
D/PanProfile( 4424): Bluetooth service connected
D/BluetoothMap( 4424): Proxy object connected
D/MapProfile( 4424): Bluetooth service connected
D/BluetoothMap( 4424): getConnectedDevices()
V/BluetoothFtpReceiver( 3606): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterState( 3606): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothMap( 4424): Bluetooth is Not enabled
D/AuthorizationBluetoothService( 1371): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/HeadsetService( 3606): Received stop request...Stopping profile...
I/ActivityManager( 1019): Killing 4103:com.google.android.configupdater/u0a9 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothHeadset( 1019): Proxy object disconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
D/BluetoothHeadset( 1239): Proxy object disconnected
D/A2dpService( 3606): Received stop request...Stopping profile...
D/A2dpStateMachine( 3606): Exit Disconnected: -1
D/BluetoothAdapterState( 3606): Stopping profile services that were post enabled
D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
D/TCMD    (  457): Listening for incoming client connection request
I/wpa_supplicant( 3688): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  273): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  273):  Wpa Supplicant Exiting !!
D/MDMCTBK (  273): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): Supplicant connection lost
D/MDMCTBK (  273): wifi_close_sockets: Exit
D/BluetoothA2dp( 1019): Proxy object disconnected
D/BluetoothAdapterService( 3606): Profile still running: com.android.bluetooth.hdp.HealthService
D/HidService( 3606): Received stop request...Stopping profile...
W/BluetoothHeadsetServiceJni( 3606): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3606): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3606): Received stop request...Stopping profile...
D/PanService( 3606): Received stop request...Stopping profile...
D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1019): attempted to stop reverse tether with nothing tethered
D/BluetoothPan( 1019): BluetoothPAN Proxy object disconnected
D/BluetoothTethering( 1019): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@440e7550
D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
D/BtGatt.DebugUtils( 3606): handleDebugAction() action=null
D/BtGatt.GattService( 3606): Received stop request...Stopping profile...
D/BtGatt.GattService( 3606): stop()
D/BluetoothMapService( 3606): Received stop request...Stopping profile...
D/BluetoothMapService( 3606): stop()
D/BluetoothMapService( 3606): MAP Service closeService in
D/BluetoothAdapterService( 3606): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 3606): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3606): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3606): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService( 3606): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3606): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3606): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3606): Cleaning up Bluetooth GID callback object
D/BluetoothInputDevice( 4424): Proxy object disconnected
D/HidProfile( 4424): Bluetooth service disconnected
D/BluetoothAdapterService( 3606): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3606): Cleaning up Bluetooth Health Interface...
D/BluetoothPan( 4424): BluetoothPAN Proxy object disconnected
D/PanProfile( 4424): Bluetooth service disconnected
D/BluetoothMap( 4424): Proxy object disconnected
D/MapProfile( 4424): Bluetooth service disconnected
W/BluetoothHealthServiceJni( 3606): Cleaning up Bluetooth Health object
D/Bluetoot,hAdapterService( 3606): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3606): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3606): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 3606): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3606): cleanup()
D/BluetoothMapService( 3606): MAP Service closeService in
D/BluetoothAdapterState( 3606): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3606): Setting state to 10
I/BluetoothAdapterState( 3606): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3606): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
I/BluetoothAdapterState( 3606): Entering OffState
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothInputDevice( 4424): onBluetoothStateChange: up=false
D/BluetoothPan( 1019): onBluetoothStateChange on: false
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=false
D/BluetoothPan( 4424): onBluetoothStateChange on: false
D/BluetoothMap( 4424): onBluetoothStateChange: up=false
D/BluetoothPbap( 4424): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1019): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1019): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@441270b0 mBinding = false
D/BluetoothManagerService( 1019): Sending unbind request.
D/BluetoothAdapterService( 3606): Cleaning up adapter native....
I/GKI_LINUX( 3606): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3606): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 3606): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 13 -> 10
I/BluetoothServiceJni( 3606): cleanupNative: return from cleanup
D/BluetoothAdapterService( 3606): Done cleaning up adapter native....
D/BluetoothAdapterService(1111103072)( 3606): ****onDestroy()********
D/BtGatt.GattService( 3606): cleanup()
W/bt-btif ( 3606): GATTC Module not enabled/already disabled
W/bt-btif ( 3606): GATTS Module not enabled/already disabled
D/BluetoothAdapter( 1081): 1112577816: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
W/ContextImpl( 4424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothAdapter( 1202): 1114495752: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1202): 1114495752: getState() :  mService = null. Returning STATE_OFF
D/DockEventReceiver( 4424): finishStartingService: stopping service
D/BluetoothAdapter( 4424): 1111152616: getState() :  mService = null. Returning STATE_OFF
V/BluetoothFtpReceiver( 3606): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3606): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 3606): Ftp Service onDestroy
V/BluetoothFtpService( 3606): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3606): Shutdown
I/ActivityManager( 1019): Killing 3973:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
D/AuthorizationBluetoothService( 1371): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4466 uid=10016 gids={50016, 3002}
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/WifiStateMachine( 1019): setWifiState: disabled
D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
W/Settings( 4263): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1261): Active network info is not available
E/XTCC-3.0.0.2(  610): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  610): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  610): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  610): [CSMgr] handleConnectivtyStatusChange failed
,W/Settings( 1202): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapter( 4424): 1111152616: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager( 1019): Killing 4263:com.google.android.talk/u0a70 (adj 15): empty #9
,D/Checkin ( 4466): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/NetlinkEvent(  270): Unexpected netlink message. type=0x11
W/Netd    (  270): No subsystem found in netlink event
D/TCMD    (  457): NL - Read 444 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 17
D/TCMD    (  457): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  273): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  273): set_property_value, Enter
,I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
I/MDMCTBK (  273): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
,E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  457): NL - Read 1000 bytes from update socket.
D/TCMD    (  457): NL - message type is RTM_NEWLINK
,D/TCMD    (  457): Listening for incoming client connection request
,D/NetlinkEvent(  270): Unexpected netlink message. type=0x11
W/Netd    (  270): No subsystem found in netlink event
D/TCMD    (  457): NL - Read 444 bytes from update socket.
D/TCMD    (  457): NL - ignore NL message, type = 17
D/TCMD    (  457): Listening for incoming client connection request
I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  273): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  273): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  273): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  273): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
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
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196614
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 2085): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs],
,I/MDMCTBK (  273): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  273): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
,I/MDMCTBK (  273): checkDefaultInst, pid match
,V/AlarmManager( 1019): sending alarm Alarm{42b90c40 type 2 android}
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1261): Active network info is not available
,D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/XTWiFiOS( 1261): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1261): Active network info is not available
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1539): Registering with Alarm Manager to restart CCE
D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/PollingManager( 1539): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1539): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/PollingManager( 1539): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 1539): [debug] > CusSM.onRadioDown
,E/ActivityThread( 1539): Failed to find provider info for com.motorola.blur.setupprovider
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=4504 uid=10030 gids={50030, 3003, 1028, 1015}
D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,V/MmsConfig( 4504): mnc/mcc: 
V/MmsConfig( 4504): tag: bool value: enabledMMS - true
,V/MmsConfig( 4504): tag: int value: maxMessageSize - 307200
V/MmsConfig( 4504): tag: int value: maxImageHeight - 1944
V/MmsConfig( 4504): tag: int value: maxImageWidth - 2592
V/MmsConfig( 4504): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 4504): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 4504): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 4504): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 4504): tag: int value: recipientLimit - 20
V/MmsConfig( 4504): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 4504): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 4504): tag: bool value: enableSlideDuration - true
V/MmsConfig( 4504): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 4504): tag: int value: maxSubjectLength - 80
V/MmsConfig( 4504): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 4504): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 4504): tag: bool value: enableGroupMms - false
,E/MmsConfig( 4504): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4523 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 4304:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 4523): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4523): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4523): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4523): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4537 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4323:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4550 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3101:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 4550): Binding Chromium to main looper Looper (main, tid 1) {42392b20}
,I/LibraryLoader( 4550): Expected native library version number "",actual native library version number ""
,I/chromium( 4550): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4550): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 4550): BLUETOOTH permission is missing!
,I/Adreno-EGL( 4550): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4550): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4550): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4550): Local Branch: 
I/Adreno-EGL( 4550): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4550): Local Patches: NONE
I/Adreno-EGL( 4550): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4550): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 4550): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4550): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 4550): Starting up...
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4594 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1019): Killing 4340:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4620 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ImageResourceManager( 4594): ImageResourceManager: uninitalized
,I/iu.Environment( 4594): update battery state; isPlugged? true*
,I/iu.Environment( 4594): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 4594): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1019): Killing 4466:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
I/ActivityManager( 1019): Killing 3606:com.android.bluetooth/1002 (adj 15): empty #10
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/iu.Environment( 1385): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1385): num queued entries: 0
,I/iu.UploadsManager( 1385): num updated entries: 0
,D/DEBUG   ( 1539): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/iu.SyncManager( 1385): NEXT; no task
,W/ContextImpl( 1539): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1539): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1539): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1539): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1539): onServiceConnected()
D/GetNotificationsWS( 1539): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1539): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1539): unbindWebServices(): un-registering our AIDL callback...
,D/MobileConnectivityChangeReceiver( 4523): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4523): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 4594): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/dalvikvm( 4594): GC_FOR_ALLOC freed 377K, 5% free 16400K/17224K, paused 14ms, total 14ms
,I/dalvikvm-heap( 4594): Grow heap (frag case) to 19.785MB for 1821008-byte allocation
,D/dalvikvm( 4594): GC_FOR_ALLOC freed 14K, 5% free 18176K/19004K, paused 11ms, total 11ms
,I/iu.UploadsManager( 4594): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/iu.UploadsManager( 4594): End new media; added: 0, uploading: 0, time: 49 ms
,I/ContactLocale( 4620): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 1019): GC_EXPLICIT freed 1161K, 65% free 17993K/50276K, paused 4ms+9ms, total 93ms
,I/iu.FingerprintManager( 4594): Start processing all media
,I/iu.FingerprintManager( 4594): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4594): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4594): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4594): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 4594): Finished generating fingerprints; 0.017 seconds
,I/iu.FingerprintManager( 4594):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/WifiP2pService( 1019): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,V/AlarmManager( 1019): sending alarm Alarm{44a65930 type 2 com.android.keyguard}
,V/AlarmManager( 1019): sending alarm Alarm{44a65a08 type 3 android}
,I/GAV2    ( 4550): Thread[GAThread,5,main]: No campaign data found.
,I/ClearcutLoggerApiImpl( 1371): disconnect managed GoogleApiClient
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,V/AlarmManager( 1019): sending alarm Alarm{44a68448 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44490278 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{441ff808 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44a65ae0 type 0 com.android.vending}
,I/ActivityManager( 1019): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=4659 uid=10038 gids={50038, 3003, 1028, 1015}
,I/dalvikvm( 4659): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4659): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4659): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4659): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4659): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4659): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4659): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4659): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4659): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4659): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4659): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4659): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4659): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4659): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4659): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4659): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x037f
,I/dalvikvm( 4659): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4659): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4659): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4659): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4659): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4659): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 4659): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4659): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4659): VFY: replacing opcode 0x62 at 0x0038
,D/Ads     ( 4659): Skipping gmscore version check
,D/Finsky  ( 4659): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4659): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4659): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4659): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/Finsky  ( 4659): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4659): Total arena pages for JIT: 11
,I/dalvikvm( 4659): Total arena pages for JIT: 12
I/dalvikvm( 4659): Total arena pages for JIT: 13
,I/dalvikvm( 4659): Total arena pages for JIT: 14
,W/Finsky  ( 4659): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4659): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4659): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4659): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1019): sending alarm Alarm{42c12408 type 0 com.android.vending}
,D/Finsky  ( 4659): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/Finsky  ( 4659): [383] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1202): client connected with version: 8296000
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Killing 4424:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1019): Client connection lost with reason: 4
,V/AlarmManager( 1019): sending alarm Alarm{44050ab0 type 0 com.android.vending}
,D/Finsky  ( 4659): [375] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4659): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1019): sending alarm Alarm{441eb1b8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42c60ff8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4294a330 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427187e0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44b8d698 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{44b8d758 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4729 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 4620:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1019): sending alarm Alarm{42560b20 type 3 android}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42c64ef0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{426ae2f8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42c67b38 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{426ab7e8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d4d9f8 type 3 android}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{425f1d90 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42b8a930 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44b953b0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{441912f0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{424da660 type 3 android}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42521d20 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44b26d00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42be22a8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44246ed8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42beed58 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{4246e990 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,V/AlarmManager( 1019): sending alarm Alarm{435b9198 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 16ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-09-17-18-29.bin
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{44184f70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{441284b0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d00bd0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42448f20 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43dfac58 type 3 android}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4768): 
D/AndroidRuntime( 4768): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4768): CheckJNI is OFF
D/dalvikvm( 4768): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4768): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4768): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4768): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4768): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4768): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4768): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4768): failed to load memtrack module: -2
D/AndroidRuntime( 4768): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10457 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3559:com.test.thalitest/u0a457 (adj 9): stop com.test.thalitest
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{44b153a0 u0 com.test.thalitest/.MainActivity t3}
I/WindowState( 1019): WIN DEATH: Window{44a7f018 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1019): Client connection lost with reason: 4
W/PackageSettings( 1019): Skipping PackageSetting{42656320 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10457 user=0: pkg removed
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4785 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449748284
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/Launcher( 1294): Deferring update until onResume
D/dalvikvm( 2085): GC_EXPLICIT freed 6163K, 44% free 9754K/17224K, paused 2ms+10ms, total 91ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
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
D/dalvikvm( 1385): GC_EXPLICIT freed 1896K, 30% free 12075K/17224K, paused 76ms+40ms, total 172ms
D/dalvikvm( 1294): GC_EXPLICIT freed 2900K, 33% free 11630K/17224K, paused 7ms+4ms, total 82ms
I/Launcher( 1294): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
D/dalvikvm( 2130): GC_EXPLICIT freed 3852K, 42% free 10082K/17224K, paused 23ms+5ms, total 129ms
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10457 #1
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449748284
D/VoicemailCleanupService( 4785): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4811 uid=10033 gids={50033, 3003, 1028, 1015}
D/dalvikvm( 1019): GC_EXPLICIT freed 1867K, 64% free 18145K/50276K, paused 22ms+12ms, total 213ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 101ms
D/AndroidRuntime( 4768): Shutting down VM
D/dalvikvm( 4768): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
I/ActivityManager( 1019): Killing 4504:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InternalIcingCorporaPro( 2130): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4827 uid=10059 gids={50059, 3003, 1028, 1015}
D/dalvikvm( 1019): GC_EXPLICIT freed 78K, 64% free 18154K/50276K, paused 4ms+13ms, total 98ms
I/ActivityManager( 1019): Killing 4523:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InternalIcingCorporaPro( 2130): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
I/ContactLocale( 4785): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
E/MP-Decision( 1471): Error(-22) changing core 3 status to offline
E/MP-Decision( 1471): Error(-22) changing core 2 status to offline

```
