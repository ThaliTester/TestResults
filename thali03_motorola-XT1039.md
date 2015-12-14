#### Test 50650278e3ff7c2_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{431d04a8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3543): 
D/AndroidRuntime( 3543): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3543): CheckJNI is OFF
D/dalvikvm( 3543): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3543): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3543): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3543): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3543): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3543): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3543): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3543): failed to load memtrack module: -2
D/AndroidRuntime( 3543): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3543
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3559 uid=10467 gids={50467, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3543): Shutting down VM
D/dalvikvm( 3543): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 26ms
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
V/WebViewChromiumFactoryProvider( 3559): Binding Chromium to main looper Looper (main, tid 1) {41f75940}
I/LibraryLoader( 3559): Expected native library version number "",actual native library version number ""
I/chromium( 3559): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3559): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d71058:true
D/BluetoothAdapter( 3559): 1106812752: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3559): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3559): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3559): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3559): Local Branch: 
I/Adreno-EGL( 3559): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3559): Local Patches: NONE
I/Adreno-EGL( 3559): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3559): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3559): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3559): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3559): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3559): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3559): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3559): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3559): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3559): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3559): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3559): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3559): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3559): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3559): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3559): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3559): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3559): Enabling debug mode 0
,W/AwContents( 3559): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3559): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,399
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +367ms (total +399ms)
,D/JsMessageQueue( 3559): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3559): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f79df0
,D/dalvikvm( 3559): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f79df0
D/jxcore_app_log( 3559): JniHelper::setJavaVM(0x415c1fa8), pthread_self() = 1614216920
,D/JX-Cordova( 3559): jxcore cordova android initializing
,I/dalvikvm( 3559): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3559): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3559): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3559): GC_CONCURRENT freed 2782K, 17% free 14420K/17224K, paused 3ms+3ms, total 60ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 164K, 17% free 14369K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 307K, 17% free 14432K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.265MB for 144892-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 267K, 17% free 14469K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.370MB for 217334-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 370K, 18% free 14543K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.545MB for 325996-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 572K, 19% free 14665K/17904K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 16.820MB for 488990-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 870K, 20% free 14841K/18384K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 17.225MB for 733480-byte allocation
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 1294K, 21% free 15099K/19104K, paused 28ms, total 28ms
,D/dalvikvm( 3559): GC_CONCURRENT freed 1676K, 20% free 15471K/19104K, paused 2ms+3ms, total 36ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 383K, 20% free 15429K/19104K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 18.673MB for 1650320-byte allocation
,D/dalvikvm( 3559): GC_CONCURRENT freed 1636K, 23% free 16001K/20716K, paused 2ms+3ms, total 39ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 1437K, 23% free 16084K/20716K, paused 31ms, total 31ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 20.100MB for 2475476-byte allocation
,D/dalvikvm( 3559): GC_CONCURRENT freed 173K, 21% free 18479K/23136K, paused 4ms+8ms, total 51ms
,D/dalvikvm( 3559): GC_CONCURRENT freed 4474K, 27% free 17060K/23136K, paused 1ms+7ms, total 52ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 48ms
,I/dalvikvm-heap( 3559): Grow heap (frag case) to 22.234MB for 3713210-byte allocation
,D/dalvikvm( 3559): GC_CONCURRENT freed 2815K, 33% free 18141K/26764K, paused 2ms+7ms, total 48ms
,D/dalvikvm( 3559): GC_FOR_ALLOC freed 707K, 33% free 18001K/26764K, paused 28ms, total 28ms
,W/jxcore-log( 3559): Initializing JXcore engine
,W/jxcore-log( 3559): JXcore engine is ready
,D/dalvikvm( 3559): GC_CONCURRENT freed 358K, 23% free 20620K/26764K, paused 2ms+2ms, total 38ms
,D/dalvikvm( 3559): WAIT_FOR_CONCURRENT_GC blocked 29ms
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
,W/Settings( 1225): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothManagerService( 1019): Message: 1
,D/BluetoothManagerService( 1019): MESSAGE_ENABLE: mBluetooth = null
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1255): Active network info is not available
,D/WifiService( 1019): New client listening to asynchronous messages
,I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3613 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
D/WifiService( 1019): setWifiEnabled: true pid=3559, uid=10467
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/Settings( 1225): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1019): setting operational mode to 1
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
D/WifiStateMachine( 1019): processMsg: InitialState
I/jxcore-log( 3559): Radios toggled
I/jxcore-log( 3559): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3559): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3559): 
W/Settings( 1225): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3559): Perf Test app loaded loaded
I/jxcore-log( 3559): 
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1225): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,I/jxcore-log( 3559): check test folder
I/jxcore-log( 3559): 
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3559): found test : ./testFindPeers.js
I/jxcore-log( 3559): 
W/XTWiFiOS( 1255): Active network info is not available
,I/jxcore-log( 3559): found test : ./testSendData.js
I/jxcore-log( 3559): 
,D/AdapterServiceConfig( 3613): Adding HeadsetService
D/AdapterServiceConfig( 3613): Adding A2dpService
D/AdapterServiceConfig( 3613): Adding HidService
D/AdapterServiceConfig( 3613): Adding HealthService
D/AdapterServiceConfig( 3613): Adding PanService
D/AdapterServiceConfig( 3613): Adding GattService
,D/AdapterServiceConfig( 3613): Adding BluetoothMapService
,D/BluetoothAdapterService( 3613): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothManagerService( 1019): Message: 20
D/BluetoothAdapterState( 3613): make
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43cda758:true
,I/bluedroid( 3613): init
,I/BluetoothAdapterState( 3613): Entering OffState
I/bte_conf( 3613): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3613): get_profile_interface socket
,I/GKI_LINUX( 3613): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1019): Message: 40
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 3613): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothAdapterProperties( 3613): Name is: XT1039
D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
,I/bluedroid( 3613): config_hci_snoop_log
D/BluetoothManagerService( 1019): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3613): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3613): Setting state to 11
I/BluetoothAdapterState( 3613): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3613): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothBondStateMachine( 3613): make
,D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3613): StableState(): Entering Off State
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3644 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1019): Proxy object connected
D/BluetoothHeadset( 1242): Proxy object connected
D/BluetoothHeadset( 1242): Proxy object connected
D/BluetoothHeadset( 1242): Proxy object connected
D/HeadsetService( 3613): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3613): classInitNative: succeeds
D/HeadsetStateMachine( 3613): Version 1.6
D/HeadsetStateMachine( 3613): make
,I/BluetoothAdapterState( 3613): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3613): get_profile_interface handsfree
,D/BluetoothA2dp( 1019): Proxy object connected
D/A2dpService( 3613): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3613): classInitNative: succeeds
,V/Avrcp   ( 3613): make
,I/bluedroid( 3613): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 3613): classInitNative: succeeds
,D/A2dpStateMachine( 3613): make
,I/bluedroid( 3613): get_profile_interface a2dp
,I/GKI_LINUX( 3613): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3613): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3613): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3613): classInitNative: succeeds
D/HidService( 3613): Received start request. Starting profile...
,I/bluedroid( 3613): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3613): classInitNative: succeeds
,D/HealthService( 3613): Received start request. Starting profile...
,I/bluedroid( 3613): get_profile_interface health
,I/BluetoothPanServiceJni( 3613): classInitNative(L105): succeeds
,D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
D/PanService( 3613): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3613): initializeNative(L110): pan
,I/bluedroid( 3613): get_profile_interface pan
,D/BluetoothTethering( 1019): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1019): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43cb3190
,I/BtGatt.JNI( 3613): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3613): handleDebugAction() action=null
D/BtGatt.GattService( 3613): Received start request. Starting profile...
D/BtGatt.GattService( 3613): start()
,I/bluedroid( 3613): get_profile_interface gatt
,D/BluetoothMapService( 3613): Received start request. Starting profile...
,D/BluetoothMapService( 3613): start()
,D/HeadsetPhoneState( 3613): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 3613): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3613): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3613): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3613): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3613): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3613): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3613): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3613): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3613): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3613): enable
,I/ActivityManager( 1019): Killing 3280:com.android.calendar/u0a7 (adj 15): empty #9
I/bt_hci_bdroid( 3613): init
I/bt_vendor( 3613): bt-vendor : init
I/bt_hci_bdroid( 3613): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3613): userial_init
I/bt_hwcfg( 3613): Starting hciattach daemon
I/bt_hwcfg( 3613): try to set false
I/chromium( 3559): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/bt_hwcfg( 3613): Starting hciattach daemon
,I/bt_hwcfg( 3613): try to set true
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/bt_hci_bdroid( 3613): bt_hc_worker_thread started
,I/qcom-bluetooth( 3675): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/WifiService( 1019): New client listening to asynchronous messages
I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  275): NetlinkHandler, interfaceAdded
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
E/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  275): , Wifi = 0
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/TCMD    (  459): NL - Read 1004 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
D/TCMD    (  459): Listening for incoming client connection request
D/Tethering( 1019): InitialState.processMessage what=4
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is add
I/MDMCTBK (  275): NetlinkHandler, interfaceAdded
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
E/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+,iface and propVal not null
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  275): , Wifi = 0
I/MDMCTBK (  275): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  459): NL - Read 1004 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
,D/QsoftapCmd(  272): Got softap fwreload command we are passing on
,D/SoftapController(  272): Softap fwReload - Ok
,I/qcom-bluetooth( 3684): /system/etc/init.qcom.bt.sh: Transport : smd 
,V/BluetoothFtpReceiver( 3613): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,I/qcom-bluetooth( 3685): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/AuthorizationBluetoothService( 1993): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring down wlan0
,I/qcom-bluetooth( 3688): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
I/qcom-bluetooth( 3689): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,I/qcom-bluetooth( 3690): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,D/WifiStateMachine( 1019): setWifiState: enabling
,I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1255): Active network info is not available
,E/Diag_Lib( 3693): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3693): Setting internal use port to rmnet0
E/Diag_Lib( 3693):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3693): Failed on DIAG init
E/Diag_Lib( 3693): linux_qmi_qmux_if_client_get_proc_name: pid=3693, proc_name=hci_qcomm_init
E/Diag_Lib( 3693): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3693): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3693): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3693): qmi_client [3693]: successfully connected to server, attempt=1
E/Diag_Lib( 3693): linux_qmi_qmux_if_client_get_client_id [3693]: qmux_client_id=13
E/Diag_Lib( 3693): qmi_client [3693] 13: qmux_client ID is initialized
E/Diag_Lib( 3693): qmi_client [3693] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3693): qmi_client [3693] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3693): qmi_client [3693] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3693): Sending signal ...... to read cmd data 
E/Diag_Lib( 3693): qmi error code.........:0
E/Diag_Lib( 3693): qmi sys error code.........:0
E/Diag_Lib( 3693): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3693): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3693): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3693): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3693): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3693): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3693): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3693): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3693): qmi_init:  Created client handle b7809788
,E/Diag_Lib( 3693): qmi_client [3693] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3693): qmi_client [3693] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3693): Sending signal ...... to read cmd data 
E/Diag_Lib( 3693): qmi error code.........:0
,E/Diag_Lib( 3693): qmi sys error code.........:0
E/Diag_Lib( 3693): Setting the api flag to : 1
,E/Diag_Lib( 3693): qmi_client [3693] 13: sending 54 bytes on fd = 8
,I/wpa_supplicant( 3694): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3694): rfkill: Cannot open RFKILL control device
D/TCMD    (  459): NL - Read 1000 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
D/TCMD    (  459): NL - Read 1000 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
,E/Diag_Lib( 3694): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3694): Setting internal use port to rmnet0
I/rmt_storage(  423): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75101d0
I/rmt_storage(  423): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
,I/rmt_storage(  423): wakelock acquired: 1, error no: 42
I/rmt_storage(  423): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1219427784)
E/Diag_Lib( 3693): qmi_client [3693] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3693):  API Flag .............. 1 
E/Diag_Lib( 3693):  Message ID ............... 92 
,E/wpa_supplicant( 3694): baseband property is set to [msm]
,E/wpa_supplicant( 3694):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3694): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3694): card_info[i].card_state: 0x2
E/wpa_supplicant( 3694): card_info[i].error_code: 0x3
E/wpa_supplicant( 3694): SIM/USIM not ready
,E/wpa_supplicant( 3694): Error while reading SIM card status
,E/wpa_supplicant( 3694): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3694): card_info[i].card_state: 0x2
E/wpa_supplicant( 3694): card_info[i].error_code: 0x3
E/wpa_supplicant( 3694): SIM/USIM not ready
,I/wpa_supplicant( 3694): eap_proxy: Card not ready
,E/Diag_Lib( 3693): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3693): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3693): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3693): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3693): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3693): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3693): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3693): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3693): qmi_client [3693] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3693): qmi_client [3693] 13: Received 880 bytes on fd = 8
,E/Diag_Lib( 3693): Sending signal ...... to read cmd data 
E/Diag_Lib( 3693): qmi error code.........:0
E/Diag_Lib( 3693): qmi sys error code.........:0
E/Diag_Lib( 3693): qmi_release: Released client handle ff
E/Diag_Lib( 3693): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/,Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3693): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3693): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3693): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3693): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3693): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3693): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3693): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3693): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3693): qmi_client [3693] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3693): qmi_client [3693] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3693): Sending signal ...... to read cmd data 
E/Diag_Lib( 3693): qmi error code.........:0
E/Diag_Lib( 3693): qmi sys error code.........:0
E/Diag_Lib( 3693): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3693] 13
,E/Diag_Lib( 3693): qmi_client [3693] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3693): qmi_client [3693] 13: failed to locate client data
E/Diag_Lib( 3693): qmi_client [3693] 13: calling release of fd=8
,E/Diag_Lib( 3693): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,I/rmt_storage(  423): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  423): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  423): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1219427784) wakelock released: 1, error no: 0
I/rmt_storage(  423): 
,I/rmt_storage(  423): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb75101d0
,D/Checkin ( 2136): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2136): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/qcom-bluetooth( 3698): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/wpa_supplicant( 3694): Long line in configuration file truncated
,I/wpa_supplicant( 3694): rfkill: Cannot open RFKILL control device
D/TCMD    (  459): NL - Read 1000 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
,I/qcom-bluetooth( 3699): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/wpa_supplicant( 3694): COUNTRY Code Recived
,E/wpa_supplicant( 3694): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3694): baseband property is set to [msm]
,E/wpa_supplicant( 3694):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3694): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3694): card_info[i].card_state: 0x2
E/wpa_supplicant( 3694): card_info[i].error_code: 0x3
E/wpa_supplicant( 3694): SIM/USIM not ready
,E/wpa_supplicant( 3694): Error while reading SIM card status
E/wpa_supplicant( 3694): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3694): card_info[i].card_state: 0x2
E/wpa_supplicant( 3694): card_info[i].error_code: 0x3
E/wpa_supplicant( 3694): SIM/USIM not ready
,I/wpa_supplicant( 3694): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): deferMessage: msg=131144
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1019): deferMessage: msg=131085
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
,D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
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
I/SBar.NetworkController( 1082): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/bt_hwcfg( 3613): bluetooth satus is on
D/bt_userial_mct( 3613): userial_open(port:0)
I/bt_userial_vendor( 3613): Done intiailizing UART
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
I/bt_userial_vendor( 3613): Done intiailizing UART
I/bt_userial_mct( 3613): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3613): Bluetooth Firmware and smd is initialized
,W/XTWiFiOS( 1255): Active network info is not available
I/GKI_LINUX( 3613): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3613): btu_task pending for preload complete event
,I/bt-btu  ( 3613): btu_task received preload complete event
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/bt_userial_mct( 3613): Entering userial_read_thread()
,D/WifiConfigStore( 1019): Loading config and enabling all networks
I/        ( 3613): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3613): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3613): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3613): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3613): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3613): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3613): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3613): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3613): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3613): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3613): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3613): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3613): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3613): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3613): BTE_InitTraceLevels -- TRC_BTIF
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1082): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3694): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
,D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3694): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3694): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
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
E/bt-btm  ( 3613): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f207049 
E/bt-btm  ( 3613): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f207049 
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
E/wpa_supplicant( 3694): COUNTRY Code Recived
E/wpa_supplicant( 3694): COUNTRY Code Recived
E/bt-btif ( 3613): Calling BTA_HhEnable
E/bt-btif ( 3613): btif_storage_get_adapter_property service_mask:0x140040
D/CommandListener(  272): Setting iface cfg
D/CommandListener(  272): Trying to bring up p2p0
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3613): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3613): Name is: XT1039
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:7 len:4
D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
D/BluetoothAdapterProperties( 3613): Scan Mode:21
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3613): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:8 len:0
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:3 len:48
I/bte_conf( 3613): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
I/bte_conf( 3613): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3613): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3613): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3613): hci lib postload completed
D/BluetoothAdapterState( 3613): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothPanServiceJni( 3613): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterProperties( 3613): ScanMode =  21
D/BluetoothAdapterProperties( 3613): State =  11
D/BluetoothAdapterProperties( 3613): Setting state to 12
I/BluetoothAdapterState( 3613): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3613): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:9 len:4
I/BluetoothAdapterState( 3613): Entering On State
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothAdapterProperties( 3613): Discoverable Timeout:120
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan( 1019): onBluetoothStateChange on: true
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106757456)( 3613): Get Bonded Devices being called
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1106757456)( 3613): Get Bonded Devices being called
D/BluetoothHeadset( 1242): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 11 -> 12
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): set frequency band 2
,D/BluetoothAdapterService(1106757456)( 3613): Get Bonded Devices being called
,D/BluetoothMapService( 3613): onReceive
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1019): Message: 40
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3613): STATE_ON
,D/BluetoothMapService( 3613): Map Service startRfcommSocketListener
,D/BluetoothMapService( 3613): Map Service initSocket
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131167
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
E/SharedPreferencesImpl( 1019): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine( 1019): handleMessage: X
,W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
W/BluetoothAdapter( 3613): getBluetoothService() called with no BluetoothManagerCallback
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
E/BluetoothServiceJni( 3613): SOCK FLAG = 1 ***********************
I/BluetoothAdapterProperties( 3613): adapterPropertyChangedCallback with type:7 len:4
I/qcom-bt-wlan-coex( 3714): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/BluetoothMapService( 3613): Accepting socket connection...
,D/BluetoothAdapterProperties( 3613): Scan Mode:21
,D/WifiP2pService( 1019): MCC mode enabled 0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43740848:true
,D/LocalBluetoothProfileManager( 3644): Adding local A2DP profile
,D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/BluetoothPbapService( 3613): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothPbapService( 3613): Handler(): got msg=1
,D/BluetoothManagerService( 1019): Message: 30
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiP2pService( 1019): InactiveState{ when=-44ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/WifiP2pService( 1019): P2pEnabledState{ when=-44ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/LocalBluetoothProfileManager( 3644): Adding local HEADSET profile
D/WifiP2pService( 1019): InactiveState{ when=-46ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-46ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3694): COUNTRY Code Recived
D/BluetoothManagerService( 1019): Message: 30
E/wpa_supplicant( 3694): COUNTRY Code Recived
,W/BluetoothAdapter( 3613): getBluetoothService() called with no BluetoothManagerCallback
D/WifiP2pService( 1019): InactiveState{ when=-16ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-16ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
E/BluetoothServiceJni( 3613): SOCK FLAG = 1 ***********************
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3644): Adding local MAP profile
D/BluetoothMap( 3644): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/dalvikvm( 1019): GC_EXPLICIT freed 22570K, 65% free 17906K/50328K, paused 4ms+11ms, total 149ms
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3644): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3644): finishStartingService: stopping service
,D/BluetoothAdapterService(1106757456)( 3613): Get Bonded Devices being called
,D/BluetoothA2dp( 3644): Proxy object connected
,D/A2dpProfile( 3644): Bluetooth service connected
,D/BluetoothHeadset( 3644): Proxy object connected
,D/HeadsetProfile( 3644): Bluetooth service connected
,D/BluetoothInputDevice( 3644): Proxy object connected
,D/HidProfile( 3644): Bluetooth service connected
,D/BluetoothPan( 3644): BluetoothPAN Proxy object connected
D/PanProfile( 3644): Bluetooth service connected
D/BluetoothMap( 3644): Proxy object connected
D/MapProfile( 3644): Bluetooth service connected
,D/BluetoothMap( 3644): getConnectedDevices()
,D/BluetoothPbap( 3644): Proxy object connected
,D/PbapServerProfile( 3644): Bluetooth service connected
,V/BluetoothFtpReceiver( 3613): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3613): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1993): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1993): Proximity feature is not enabled.
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3613): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3613): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3613): Accept thread started.
V/BluetoothFtpService( 3613): Ftp Service onCreate
I/BluetoothFtpService( 3613): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3613): Starting FTP service
V/BluetoothFtpService( 3613): Ftp Service onStartCommand
,V/BluetoothFtpService( 3613): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3613): Handler(): got msg=1
V/BluetoothFtpService( 3613): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3613): Ftp Service initSocket
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3613): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3613): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3613): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3613): Run Accept thread
,D/Checkin ( 2136): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2136): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/MDMCTBK (  275): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  275): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): wifi_connect_to_supplicant, current pid is = 275
D/MDMCTBK (  275): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  275): wifi_close_sockets: Exit
,E/MDMCTBK (  275): Attach monitor thread
I/MDMCTBK (  275): createWifiMonitorThread: Started the wifi monitor thread -1205351600
,D/MDMCTBK (  275): wifi_wait_on_socket: Enter monitor thread
,D/TCMD    (  459): NL - Read 1000 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
,D/Checkin ( 2136): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,D/Checkin ( 2136): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:48
D/TCMD    (  459): NL - Read 56 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
D/TCMD    (  459): Listening for incoming client connection request
I/wpa_supplicant( 3691): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3691): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 64:7c:34:12:7f:81
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 64:7c:34:12:7f:81
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 06:7c:34:12:7f:81,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 06:7c:34:12:7f:81
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 0c:bd:51:2b:c1:25
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 0c:bd:51:2b:c1:25
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 38:f8:89:11:e9:11,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 38:f8:89:11:e9:11,
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 9e:93:4e:3e:ba:c5,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 9e:93:4e:3e:ba:c5,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS ,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS ,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH ,
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
I/wpa_supplicant( 3694): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE ,
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 3694): DSDS: eapol_sm_notify_config config->sim_slot = 0,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 3694): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  459): NL - Read 312 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
D/TCMD    (  459): NL - Read 192 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
D/TCMD    (  459): Listening for incoming client connection request
I/wpa_supplicant( 3694): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  459): NL - Read 68 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
D/TCMD    (  459): Listening for incoming client connection request
D/TCMD    (  459): NL - Read 1000 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3694): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  459): NL - Read 80 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
D/TCMD    (  459): Listening for incoming client connection request
D/TCMD    (  459): NL - Read 80 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
D/TCMD    (  459): Listening for incoming client connection request
D/TCMD    (  459): NL - Read 68 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3694): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3694): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  459): NL - Read 1000 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,I/MDMCTBK (  275): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19,
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
,I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1205199456
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter,
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE ,
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
,E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-38ms what=147462 obj=android.net.wifi.StateChangeResult@4209bde0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-17ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@4216deb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427ccf28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427ccf28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 f
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 f
D/TCMD    (  459): NL - Read 56 bytes from update socket.
D/TCMD    (  459): NL - message type is RTM_NEWLINK
,D/TCMD    (  459): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 f
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 f
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 6
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 6,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c2,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 64,
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 0c
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 0c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 9e
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 6 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 fe
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 7 fe
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 fc
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 8 fc
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 64
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 9 64,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 a
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 10 a
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i,
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@42403098 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@42403098 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-9ms what=147462 obj=android.net.wifi.StateChangeResult@42403098 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  459): NL - Read 60 bytes from update socket.
D/TCMD    (  459): NL - ignore NL message, type = 20
,D/TCMD    (  459): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
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
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/jxcore-log( 3559): BLE advertisement not supported: Build version is 19
I/jxcore-log( 3559): 
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
,D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
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
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1082): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@420bb118
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
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
D/WifiStateMachine( 1019): handleMessage: X
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/SBar.NetworkController( 1082): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1270): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1270): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1270): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1082): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@420bb118
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1270): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1270): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1270): onReceive() - done, currentInetCondition=0
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ConnectedState
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/PollingManager( 1526): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,W/        ( 1019): Unable to set rtc to 1450100413: Invalid argument
,D/        ( 1019): Setting time of day to sec=1450100413
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-59ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3810 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/PollingManager( 1526): now: 217658 ,futureTime: 86439465
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,D/PollingManager( 1526): Polling alarm set to expire at: 86439465 Current Time: 217661
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,E/ActivityThread( 1526): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1526): registerApp(): CCE
I/CCE     ( 1526): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
D/CCE     ( 1526): Registering with Alarm Manager to restart CCE
,D/MMApiWebService( 1526): Received data connectivity intent from PollingManager .. retry the waiting requests: 3
D/CCE     ( 1526): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1526): isRequestAllowed(): already have outstanding request ... ignoring request
,D/PollingManager( 1526): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/OtaApp  ( 1526): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/OtaApp  ( 1526): [debug] > CusSM.onRadioUp
,D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/PollingManager( 1526): now: 217715 ,futureTime: 86439465
,D/PollingManager( 1526): Polling alarm set to expire at: 86439465 Current Time: 217719
,D/MMApiWebService( 1526): generating token using payload instead of using session token
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,E/ActivityThread( 1526): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1526): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1526): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1526): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1526): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1526): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1526): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/MMApiWSBase( 1526): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,I/MMApiWSBase( 1526): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1019): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3848 uid=10056 gids={50056, 3003, 1028, 1015}
D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 3810): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f75298, skipping init
I/openssl ( 3810): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3810): Crypto mode 0 already enabled
D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,W/dalvikvm( 1209): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1209): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1209): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
,I/dalvikvm( 1209): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1209): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1209): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1209): Using platform SSLCertificateSocketFactory
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3870 uid=10030 gids={50030, 3003, 1028, 1015}
,I/GamesSyncServiceMain( 1373): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1373): Failed to execute periodic sync, missing client context - aborting
,I/DownloadManager( 3810): Download 281 starting
,W/ActivityThread( 3810): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/PhenotypeConfigurator( 1209): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,V/MmsConfig( 3870): mnc/mcc: 
,V/MmsConfig( 3870): tag: bool value: enabledMMS - true
V/MmsConfig( 3870): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3870): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3870): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3870): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3870): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3870): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3870): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3870): tag: int value: recipientLimit - 20
V/MmsConfig( 3870): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 3870): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3870): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3870): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3870): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 3870): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3870): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3870): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3870): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3895 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3395:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/TelephonyProvider( 1242): Column apn id key is 'apn_id'
,I/dalvikvm( 1373): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1373): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1373): VFY: replacing opcode 0x6e at 0x003d
,D/GpsLocationProvider( 1019): NTP server returned: 1450100411492 (Mon Dec 14 14:40:11 CET 2015) reference: 215842 certainty: 9 system time offset: -2255
,E/ActivityThread( 1373): Failed to find provider info for com.android.contacts.metadata
D/DelayedSyncController( 3848): Delaying sync.
E/LocSvc_ApiV02( 1019): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,D/SyncManager( 1019): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 218114, reason: UserStart
,D/MobileConnectivityChangeReceiver( 3895): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3895): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 3895): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3895): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1019): Killing 3051:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/Auth.Api.Credentials( 1373): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3917 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3426:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,D/dalvikvm( 1242): GC_EXPLICIT freed 1460K, 45% free 9518K/17224K, paused 9ms+25ms, total 103ms
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1373): Checkin interval check for package: unspecified last checkin: 1449862248998 min interval config: 0 actual interval: 238164833
,I/CheckinService( 1373): Checking schedule, now: 1450100413836 next: 1449862278968
,I/CheckinService( 1373): active receiver: enabled
,I/CheckinService( 1373): Preparing to send checkin request
,I/EventLogService( 1373): Accumulating logs since 1450098901124
,I/dalvikvm( 1209): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1209): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1209): VFY: replacing opcode 0x6e at 0x003d
,I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,D/dalvikvm( 1526): GC_CONCURRENT freed 2343K, 38% free 10778K/17224K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 2010K, 65% free 17927K/50328K, paused 5ms+34ms, total 130ms
,V/WebViewChromiumFactoryProvider( 3917): Binding Chromium to main looper Looper (main, tid 1) {41f6fba0}
,I/LibraryLoader( 3917): Expected native library version number "",actual native library version number ""
,I/chromium( 3917): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3917): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3917): BLUETOOTH permission is missing!
,I/CheckinRequestBuilder( 1373): Checkin reason type: 8 attempt count: 1
,D/WifiService( 1019): New client listening to asynchronous messages
,I/Adreno-EGL( 3917): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3917): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3917): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3917): Local Branch: 
I/Adreno-EGL( 3917): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3917): Local Patches: NONE
I/Adreno-EGL( 3917): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
E/ActivityThread( 1373): Failed to find provider info for com.google.android.wearable.settings
,W/chromium( 3917): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3917): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3917): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DelayedSyncController( 3848): Delaying sync.
,I/DownloadManager( 3810): Ignoring Content-Length since Transfer-Encoding is also defined
,I/ActivityManager( 1019): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3968 uid=10064 gids={50064, 3003, 1028, 1015}
I/NSApplication( 3917): Starting up...
,I/MMApiWSBase( 1526): doRequest(): error in response: 403
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/ImageResourceManager( 3103): ImageResourceManager: uninitalized
,I/iu.Environment( 3103): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/Checkin ( 3810): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/iu.SyncManager( 3103): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 3083:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ActivityThread( 3968): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
I/MMApiWSBase( 1526): doRequest(): error in response: {"error":"INVALID_SESSION","error_text":"Please provide a valid authtoken"}
D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/iu.UploadsManager( 3103): num queued entries: 0
,I/GoogleURLConnFactory( 1373): Using platform SSLCertificateSocketFactory
,D/MMApiWSBase( 1526): doRequest(): v1/ns/list/messages resp length: 75
,I/MMApiWebService( 1526): _inspectMMApiResponse(): found an error from a web service response: ForbiddenError msg: INVALID_SESSION req: 
,I/iu.UploadsManager( 3103): num updated entries: 0
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1526): _inspectMMApiResponse(): received invalid session error from the server.. need to re-login
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1526): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiProvisionService( 1526): Got request to obtain new Session .. doing so now
D/MMApiProvisionService( 1526): isRequestAllowed(): already have outstanding request ... ignoring request
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 1526): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"172742","deviceId":"1135300315450105856"}
,D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/iu.SyncManager( 3103): NEXT; no task
D/MMApiProvisionService( 1526): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1526): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1526): MMApiProvisionService.handleResponse (update_device) : true (None)
,I/MMApiWSBase( 1526): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/check.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/iu.SyncManager( 1373): SYNC; picasa accounts
,D/MMApiProvisionService( 1526): handleResponse(): Session Expiration alarm set to expire at: Wed Dec 16 14:39:16 CET 2015
,D/NetworkLogImpl( 1373): Loaded NetworkSpeedPredictor
,D/MMApiProvisionService( 1526): _setMMApiCredInfo: storing credential info 
,I/iu.Environment( 1373): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/DownloadManager( 3810): Download 281 finished with status SUCCESS
,I/iu.UploadsManager( 1373): num queued entries: 0
,I/ActivityManager( 1019): Killing 3452:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/GAV2    ( 3968): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/DEBUG   ( 1526): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1526): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,E/MMApiProvisionService( 1526): handleResponse(): no settings sent by the server:
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/WaitableIntentService( 1526): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1526): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/MMApiWebService( 1526): MMApiWebService told us to retry waiting request since device is successfully provisioned: 1
,D/dalvikvm( 1373): GC_CONCURRENT freed 1679K, 30% free 12076K/17224K, paused 4ms+14ms, total 56ms
,I/iu.UploadsManager( 1373): num updated entries: 0
I/openssl ( 3810): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3810): Crypto mode 0 already enabled
,D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MobileConnectivityChangeReceiver( 3895): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3895): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.SyncManager( 1373): NEXT; no task
,I/iu.Environment( 3103): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/MMApiWSBase( 1526): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4004 uid=10007 gids={50007, 3003}
,D/ExtensionsFactory( 4004): No custom extensions.
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=4025 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 3125:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4037 uid=10008 gids={50008, 3003, 1028, 1015}
,D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+3ms, total 21ms
,I/ActivityManager( 1019): Killing 3644:com.android.settings/1000 (adj 15): empty #9
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1019): Client connection lost with reason: 4
I/GCM     ( 1993): GCM config loaded
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,D/dalvikvm( 1993): GC_CONCURRENT freed 1959K, 40% free 10478K/17224K, paused 11ms+7ms, total 63ms
,V/AlarmClock( 4025): AlarmInitReceiver android.intent.action.TIME_SET
,I/CalendarProvider2( 4037): Created com.android.providers.calendar.CalendarAlarmManager@41f8ed90(com.android.providers.calendar.CalendarProvider2@41f86948)
,I/AlarmClock( 4025): Displaying next alarm time: ''
,V/AlarmClock( 4025): AlarmInitReceiver finished
,I/Gmail   ( 3968): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4060 uid=10098 gids={50098}
I/Gmail   ( 3968): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3968): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3968): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/dalvikvm( 1019): GC_EXPLICIT freed 899K, 65% free 17905K/50328K, paused 4ms+11ms, total 109ms
,D/dalvikvm( 4060): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41f6eb78, skipping init
D/TimeService( 4060): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450100415012
D/        ( 4060): TimeServiceNative: User Time to be set is 1450100415013
D/QC-time-services( 4060): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4060): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4060): Lib:time_genoff_operation: pargs->ts_val = 1450100415013
,D/QC-time-services(  413): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4060): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  413): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450100415013
D/QC-time-services(  413): Daemon:genoff_opr: Base = 2, val = 1450100415013, operation = 0
D/QC-time-services(  413): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/14/115 13:34:20
D/QC-time-services(  413): Daemon:Value read from RTC seconds = 1450100060000
D/QC-time-services(  413): Daemon:new time 1450100415013 
D/QC-time-services(  413): Daemon: delta 355013 genoff 355013 
D/QC-time-services(  413): Daemon:genoff_persistent_update: Writing genoff = 355013 to memory
D/QC-time-services(  413): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  413): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  413): Updating the TOD offset
D/QC-time-services(  413): Daemon:genoff_persistent_update: Writing genoff = 355013 to memory
D/QC-time-services(  413): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  413): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  413): Daemon:Update to modem bit set
D/QC-time-services(  413): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 4060): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  413): Daemon: Base = 2, Value being sent to MODEM = 18446743757745106629
I/ActivityManager( 1019): Killing 3810:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/QC-time-services(  413): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  413): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1373): Checkin interval check for package: unspecified last checkin: 1449862248998 min interval config: 0 actual interval: 238166048
,I/Gmail   ( 3968): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12298, normalSync: true
,D/dalvikvm( 1209): GC_CONCURRENT freed 1661K, 35% free 11310K/17224K, paused 4ms+11ms, total 61ms
,I/dalvikvm( 1373): Could not find method android.content.Context.getNoBackupFilesDir, referenced from method com.google.android.gms.iid.n.<init>
W/dalvikvm( 1373): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
,D/dalvikvm( 1373): VFY: replacing opcode 0x6e at 0x002c
I/dalvikvm( 1373): Could not find method android.content.Context.getDrawable, referenced from method android.support.v4.content.g.a
W/dalvikvm( 1373): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 1373): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1373): Could not find method android.content.Context.getColor, referenced from method android.support.v4.content.g.b
W/dalvikvm( 1373): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
,D/dalvikvm( 1373): VFY: replacing opcode 0x6e at 0x0006
,D/MMApiWSBase( 1526): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1526): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1526): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/DEBUG   ( 1526): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1526): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1526): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1526): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1526): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1526): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1526
D/Checkin ( 1526): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
D/SundryService( 1526): handleGetNotificationsResponse(): got 0; more=false
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1526): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1526
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/IInputConnectionWrapper( 3559): showStatusIcon on inactive InputConnection
,I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,W/PhenotypeConfigurator( 1209): Server returned 404
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4080 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,114
,D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4089 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
W/dalvikvm( 4080): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4080): VFY: replacing opcode 0x60 at 0x000b
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/dalvikvm( 4080): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4080): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x00cd
,D/DEBUG   ( 1526): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
I/MultiDex( 4080): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4080): install
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/MultiDex( 4080): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/SundryService( 1526): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1526): Received shoulder tap
,I/MultiDex( 4080): loading existing secondary dex files
,I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{420e4708 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/MultiDex( 4080): load found 3 secondary dex files
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1270): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1270): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1270): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1270): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1082): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
I/MultiDex( 4080): install done
,D/WaitableIntentService( 1526): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,D/GetNotificationsWS( 1526): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/dalvikvm( 4080): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4080): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4080): VFY: replacing opcode 0x62 at 0x000a
D/GetNotificationsWS( 1526): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1526): ServiceHandler.handleMessage: mWaitCount=2
D/dalvikvm( 4080): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4080): VFY: unable to resolve instance field 36
,D/dalvikvm( 4080): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4080): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4080): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4080): VFY: replacing opcode 0x62 at 0x0047
,D/MMApiWSBase( 1526): doRequest(): v1/us/devices/check resp length: 2314
,D/CCE     ( 1526): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/dalvikvm( 4080): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4080): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/CCE     ( 1526): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.23016434 for reqID:  error: None
,D/dalvikvm( 4080): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f71df8
,D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/dalvikvm( 4080): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f71df8
,D/dalvikvm( 4080): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f71df8, skipping init
,D/dalvikvm( 4080): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f71df8
D/dalvikvm( 4080): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f71df8
,V/JNIHelp ( 4080): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/OtaWebService( 1526): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@427137e8 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@41ff2538
,D/OtaWebService( 1526): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"version\":\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\",\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"pollAfterSeconds\":21600,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1526): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@42714e88 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@41ff2538
,D/OtaWebService( 1526): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"version\":\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\",\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"pollAfterSeconds\":21600,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/dalvikvm( 4089): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f74600, skipping init
I/openssl ( 4089): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4089): Crypto mode 0 already enabled
I/OtaApp  ( 1526): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update : 200 :  
D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
I/MMApiWSBase( 1526): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/DEBUG   ( 1526): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1526): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1526): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 1526): onHandleIntent(): isWaitEnabled=true
,D/WaitableIntentService( 1526): ServiceHandler.handleMessage: mWaitCount=1
,I/OtaApp  ( 1526): [info] > CusSM.handleNewVersion: was notified of a new version : src Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU: dest Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU: current Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU: size 12503823
,D/OtaApp  ( 1526): [debug] > CusAndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1526): [info] > Next Polling is scheduled at 359 mins from now
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1526): [info] > Device is NOT rooted. persist.qe=qe 0/0
D/PollingManager( 1526): registerApp(): cUsPollingService
D/PollingManager( 1526): registerApp(): shortest interval is 21599000
,D/PollingManager( 1526): Polling alarm set to expire at: 21818813 Current Time: 219813
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/GCM     ( 1993): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
D/dalvikvm( 4080): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f71df8
,D/dalvikvm( 4080): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f71df8
D/dalvikvm( 4080): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f71df8
,D/dalvikvm( 4080): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f71df8
,E/OtaApp  ( 1526): [error] > UpgradeSource.isUpgradeAcceptable succeeded 
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > prevDestVersion = Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU
,W/OtaApp  ( 1526): [warn] > CusSM.handleNewVersion: already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 1526): [error] > CusSM.failNotify: notification failed from repository upgrade for reason already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK; additional information: polling initiated upgrade
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1450100415488, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 1526): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1450100415503, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,I/ActivityManager( 1019): Killing 3870:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
,D/OtaApp  ( 1526): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  NotifiedBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EUBlur_Version.21.11.56.peregrine_reteu.reteuall.en.EURepository: upgrade; Location: null; AddOnInfo: polling initiated upgrade1450100415536false
,E/DictionaryProvider:UpdateHandler( 1193): A file was downloaded but it can't be opened
E/DictionaryProvider:UpdateHandler( 1193): java.io.FileNotFoundException: No such file or directory
E/DictionaryProvider:UpdateHandler( 1193): 	at android.database.DatabaseUtils.readExceptionWithFileNotFoundExceptionFromParcel(DatabaseUtils.java:146)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentProviderProxy.openTypedAssetFile(ContentProviderNative.java:682)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentResolver.openTypedAssetFileDescriptor(ContentResolver.java:1063)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentResolver.openAssetFileDescriptor(ContentResolver.java:904)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentResolver.openFileDescriptor(ContentResolver.java:761)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentResolver.openFileDescriptor(ContentResolver.java:716)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.app.DownloadManager.openDownloadedFile(DownloadManager.java:1018)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.DownloadManagerWrapper.openDownloadedFile(DownloadManagerWrapper.java:72)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.UpdateHandler.handleDownloadedFile(UpdateHandler.java:520)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.UpdateHandler.downloadFinished(UpdateHandler.java:439)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.DictionaryService.dispatchBroadcast(DictionaryService.java:182)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.DictionaryService.access$000(DictionaryService.java:52)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.DictionaryService$1.run(DictionaryService.java:160)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.lang.Thread.run(Thread.java:841)
,I/ProviderInstaller( 4080): Installed default security provider GmsCore_OpenSSL
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; src: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; dest: Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU; upgradeSource:upgrade; Repository: upgrade; Location: null; AddOnInfo: polling initiated upgrade; reportingTag: TRIGGER-POLLING,peregrine_reteu_1411553875137; trackingId: 2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007; metaDataVersion: 1410862052; ro.carrier: reteu. time: 1450100415
,I/OtaApp  ( 1526): [info] > retrieving device info from cce
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/BSUtils ( 1526): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,E/DictionaryProvider:UpdateHandler( 1193): A file was downloaded but it can't be opened
E/DictionaryProvider:UpdateHandler( 1193): java.io.FileNotFoundException: No such file or directory
E/DictionaryProvider:UpdateHandler( 1193): 	at android.database.DatabaseUtils.readExceptionWithFileNotFoundExceptionFromParcel(DatabaseUtils.java:146)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentProviderProxy.openTypedAssetFile(ContentProviderNative.java:682)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentResolver.openTypedAssetFileDescriptor(ContentResolver.java:1063)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentResolver.openAssetFileDescriptor(ContentResolver.java:904)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentResolver.openFileDescriptor(ContentResolver.java:761)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.content.ContentResolver.openFileDescriptor(ContentResolver.java:716)
E/DictionaryProvider:UpdateHandler( 1193): 	at android.app.DownloadManager.openDownloadedFile(DownloadManager.java:1018)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.DownloadManagerWrapper.openDownloadedFile(DownloadManagerWrapper.java:72)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.UpdateHandler.handleDownloadedFile(UpdateHandler.java:520)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.UpdateHandler.downloadFinished(UpdateHandler.java:439)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.DictionaryService.dispatchBroadcast(DictionaryService.java:182)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.DictionaryService.access$000(DictionaryService.java:52)
E/DictionaryProvider:UpdateHandler( 1193): 	at com.android.inputmethod.dictionarypack.DictionaryService$1.run(DictionaryService.java:160)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DictionaryProvider:UpdateHandler( 1193): 	at java.lang.Thread.run(Thread.java:841)
,D/WearableService( 1209): callingUid 10022, callindPid: 1209
,I/OtaApp  ( 1526): [info] > Received deviceInfo from cce : 
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/OtaApp  ( 1526): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update handle new version returned false
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450100415
,I/OtaWebService( 1526): [info] > Received web service call for request :v1/us/devices/state
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaWebService( 1526): [debug] > appending web service request to serviceHandler
,D/OtaApp  ( 1526): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
,I/dalvikvm( 4080): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
,W/dalvikvm( 4080): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x00ce
,I/dalvikvm( 4080): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4080): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1373): Restart initialization of location
,E/MDM     ( 1209): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1993): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1993): Proximity feature is not enabled.
I/dalvikvm( 4080): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4080): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4080): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4080): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
D/dalvikvm( 4080): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4080): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4080): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x0036
D/dalvikvm( 1526): GC_CONCURRENT freed 1965K, 37% free 10860K/17224K, paused 4ms+6ms, total 51ms
,D/dalvikvm( 1526): WAIT_FOR_CONCURRENT_GC blocked 37ms
D/OtaApp  ( 1526): [debug] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: authoritative response from BOTA ERR_NOTFOUND
,D/dalvikvm( 1526): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/dalvikvm( 1526): WAIT_FOR_CONCURRENT_GC blocked 19ms
I/dalvikvm( 4080): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4080): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4080): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450100415
I/openssl ( 4089): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4089): Crypto mode 0 already enabled
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,W/GCoreFlp( 1209): No location to return for getLastLocation()
,W/FusedLocationProvider( 1209): location=null
,I/OtaApp  ( 1526): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: server told to :wait
,D/OtaWebService( 1526): [debug] > appending web service response to serviceHandler
D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(v1/us/devices/state)
,D/OtaWebService( 1526): [debug] > Removing request :v1/us/devices/check from queue
,I/MMApiWSBase( 1526): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/state.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,E/AppDataSearchClient( 1193): GetCorpusHandlesRegisteredForIME failed.
E/AppDataSearchClient( 1193): android.os.RemoteException
E/AppDataSearchClient( 1193): 	at com.google.android.gms.internal.dg.getSearchService(Unknown Source)
E/AppDataSearchClient( 1193): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.getCorpusHandlesRegisteredForIME(Unknown Source)
E/AppDataSearchClient( 1193): 	at com.android.inputmethod.latin.amanatto.AmanattoDataUpdaterHelper$3.run(AmanattoDataUpdaterHelper.java:163)
E/AppDataSearchClient( 1193): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AppDataSearchClient( 1193): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AppDataSearchClient( 1193): 	at java.lang.Thread.run(Thread.java:841)
E/AppDataSearchClient( 1193): 	at com.android.inputmethod.latin.amanatto.AmanattoDataUpdaterHelper$BackgroundThreadFactory$1.run(AmanattoDataUpdaterHelper.java:68)
E/AppDataSearchClient( 1193): Caused by: java.lang.IllegalStateException: Not connected. Call connect() and wait for onConnected() to be called.
E/AppDataSearchClient( 1193): 	at com.google.android.gms.internal.eg.bU(Unknown Source)
E/AppDataSearchClient( 1193): 	at com.google.android.gms.internal.eg.bV(Unknown Source)
E/AppDataSearchClient( 1193): 	... 7 more
,E/AmanattoDataUpdater( 1193): Cannot get corpus handles.
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450100415
,I/CalendarProvider2( 4037): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4037): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/AlertReceiver( 4004): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4004): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/DrmWidevineDash(  279): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
,D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  279): App is not loaded in QSEE
E/QSEECOMAPI: (  279): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  279): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  279): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  279): App is not loaded in QSEE
,I/dalvikvm( 4080): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 4080): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x003d
,W/dalvikvm( 4080): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4080): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4080): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 4080): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4080): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x00bb
,D/NativeLibraryUtils( 4080): Install completed successfully. count=14 extracted=0
,I/GoogleURLConnFactory( 4080): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  279): Loaded image: APP id = 3
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5339000
,E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5339000
,D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
,I/ActivityManager( 1019): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4143 uid=10065 gids={50065, 3003}
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=702056791
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,W/AbstractGoogleClient( 4143): Application name is not set. Call Builder#setApplicationName.
,D/MMApiWSBase( 1526): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1526): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1526): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/dalvikvm( 1526): Jit: resizing JitTable from 4096 to 8192
,D/Checkin ( 1526): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1526): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1526): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1526): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1526): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1526): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1526): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1526): unbindWebServices(): un-registering our AIDL callback...
,I/dalvikvm( 1373): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1373): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1373): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 1373): DexOpt: --- BEGIN 'ads575260623.jar' (bootstrap=0) ---
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4163): DexOpt: load 4ms, verify+opt 11ms, 192820 bytes
,D/dalvikvm( 1373): DexOpt: --- END 'ads575260623.jar' (success) ---
,D/dalvikvm( 1373): DEX prep '/data/data/com.google.android.gms/cache/ads575260623.jar': unzip in 0ms, rewrite 108ms
,I/PhenotypeConfigurator( 1209): Scheduling Phenotype for one-off execution 11801 seconds from now (1450100416297)
,D/GetConfigurationSnapshotOperation( 1209): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1209): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1209): Using platform SSLCertificateSocketFactory
,D/MMApiWSBase( 1526): doRequest(): v1/us/devices/state resp length: 2224
,D/CCE     ( 1526): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1526): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.-1644124099 for reqID:  error: None
,D/OtaWebService( 1526): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@420b2c88 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@42130120
,D/OtaWebService( 1526): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1526): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@42431d18 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@42130120
,D/OtaWebService( 1526): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaApp  ( 1526): [debug] > Inside handleMMApiUpgradeStatusResponse
,D/OtaApp  ( 1526): [debug] > exec delete from status where _id=1
,D/dalvikvm( 4080): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42335510
D/dalvikvm( 4080): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42335510
,D/dalvikvm( 4080): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42335510, skipping init
,D/OtaApp  ( 1526): [debug] > stopTimer, cancel()
,D/OtaApp  ( 1526): [debug] > handleMMApiUpgradeStatusResponse server told to : continue
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
,D/OtaApp  ( 1526): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  ResultBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EUBlur_Version.21.11.56.peregrine_reteu.reteuall.en.EUalready working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK1450100416644false
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; src: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; dest: Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU; upgradeSource:upgrade; already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK; reportingTag: TRIGGER-POLLING,peregrine_reteu_1411553875137; trackingId: 2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007; metaDataVersion: 1410862052; ro.carrier: reteu. time: 1450100415
,I/OtaApp  ( 1526): [info] > retrieving device info from cce
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/BSUtils ( 1526): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/OtaApp  ( 1526): [info] > Received deviceInfo from cce : 
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaWebService( 1526): [info] > Received web service call for request :v1/us/devices/state
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaWebService( 1526): [debug] > appending web service request to serviceHandler
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1526): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(v1/us/devices/state)
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 1526): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaWebService( 1526): [debug] > appending web service response to serviceHandler
,D/OtaApp  ( 1526): [debug] > UpdateReceiver: Received True from doSanityCheck.
,D/OtaWebService( 1526): [debug] > Removing request :v1/us/devices/state from queue
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1526
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1019): GC_EXPLICIT freed 882K, 65% free 17885K/50328K, paused 6ms+14ms, total 125ms
,I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/MMApiWSBase( 1526): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/state.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,W/Settings( 4080): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 1209): GC_CONCURRENT freed 1535K, 32% free 11747K/17224K, paused 2ms+7ms, total 38ms
,D/CalendarSyncAdapter( 4143): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 1019): Killing 3895:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WVCdm   (  279): CdmEngine::OpenSession
D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,I/ActivityManager( 1019): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4177 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=2444836964
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/MMApiWSBase( 1526): doRequest(): v1/us/devices/state resp length: 2224
,D/CCE     ( 1526): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1526): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.145644235 for reqID:  error: None
,D/OtaWebService( 1526): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@420b2d28 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@421c4300
,D/OtaWebService( 1526): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1526): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@420b8960 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@421c4300
,D/OtaWebService( 1526): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaApp  ( 1526): [debug] > Inside handleMMApiUpgradeStatusResponse
,D/OtaApp  ( 1526): [debug] > exec delete from status where _id=2
,D/dalvikvm( 1526): GC_CONCURRENT freed 2016K, 38% free 10849K/17224K, paused 2ms+3ms, total 32ms
,D/OtaApp  ( 1526): [debug] > stopTimer, have stoped, do nothing
,D/OtaApp  ( 1526): [debug] > handleMMApiUpgradeStatusResponse server told to : continue
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1526): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1526): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1526): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1526): [debug] > UpdateReceiver: Received True from doSanityCheck.
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1526): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1526
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaWebService( 1526): [debug] > appending web service response to serviceHandler
,D/OtaWebService( 1526): [debug] > Removing request :v1/us/devices/state from queue
,D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
,D/OtaWebService( 1526): [debug] > No pending web request. shutdown webservice
,I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaWebService( 1526): [info] > Stopping webservice android service
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/ContactLocale( 4177): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm( 4080): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4192): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 3968): GC_EXPLICIT freed 5140K, 44% free 9740K/17224K, paused 3ms+5ms, total 56ms
,D/dalvikvm( 4080): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4080): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 93ms
,I/Adreno-EGL( 4080): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4080): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4080): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4080): Local Branch: 
I/Adreno-EGL( 4080): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4080): Local Patches: NONE
I/Adreno-EGL( 4080): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Gmail   ( 3968): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12816, normalSync: true
,I/Gmail   ( 3968): lowestBackward conversation id 0
,I/Adreno-EGL( 4080): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4080): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4080): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4080): Local Branch: 
I/Adreno-EGL( 4080): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4080): Local Patches: NONE
I/Adreno-EGL( 4080): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1019): Killing 3848:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Adreno-EGL( 4080): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4080): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4080): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4080): Local Branch: 
I/Adreno-EGL( 4080): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4080): Local Patches: NONE
I/Adreno-EGL( 4080): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1993): GC_EXPLICIT freed 1733K, 39% free 10549K/17224K, paused 10ms+5ms, total 67ms
,I/Adreno-EGL( 4080): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4080): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4080): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4080): Local Branch: 
I/Adreno-EGL( 4080): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4080): Local Patches: NONE
I/Adreno-EGL( 4080): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/PeopleSync( 1373): onPerformSync() [5005f081]
,D/dalvikvm( 1373): GC_CONCURRENT freed 1817K, 29% free 12236K/17224K, paused 5ms+6ms, total 49ms
,W/SQLiteConnectionPool( 1373): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/CheckinRequestBuilder( 1373): Classify the device as Phone.
,I/PeopleSync( 1373): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1373): Starting sync, feed=null [5005f081]
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,I/PeopleSync( 1373): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/CheckinTask( 1373): Sending checkin request (12625 bytes)
,D/dalvikvm( 1373): GC_CONCURRENT freed 1850K, 29% free 12395K/17224K, paused 5ms+5ms, total 44ms
,I/ActivityManager( 1019): Killing 3103:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 1373): Jit: resizing JitTable from 4096 to 8192
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,W/BaseAppContext( 1373): Using Auth Proxy for data requests.
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4218 uid=10059 gids={50059, 3003, 1028, 1015}
,D/dalvikvm( 1993): GC_EXPLICIT freed 882K, 39% free 10633K/17224K, paused 3ms+5ms, total 34ms
,I/CheckinResponseProcessor( 1373): From server: 2 gservices updates and 0 deletes
,E/UlpEngine( 1019): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,E/UlpEngine( 1019): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
I/CertBlacklister( 1019): Certificate blacklist changed, updating...
I/CertBlacklister( 1019): Certificate blacklist updated
,I/GservicesProvider( 1993): main difference update completed
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,I/ActivityManager( 1019): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4231 uid=10009 gids={50009, 3003, 2001}
,I/CheckinRequestBuilder( 1373): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1373): Failed to find provider info for com.google.android.wearable.settings
,W/ContextImpl( 4231): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,W/ActiveOrDefaultContextProvider( 4218): Missing scope.enter somewhere. Returning default context
,I/UpdateFetcherService( 4231): Update started
,E/UpdateRequestReceiver( 4231): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/GAV2    ( 3917): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 4231): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/openssl ( 4089): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4089): Crypto mode 0 already enabled
E/UpdateRequestReceiver( 4231): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/UpdateFetcherService( 4231): Update started
,E/UpdateRequestReceiver( 4231): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4231): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager( 1019): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4271 uid=10025 gids={50025, 3003}
,W/GAV2    ( 4218): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/ActivityThread( 4218): Failed to find provider info for com.google.android.apps.docs.editors.kix.statesyncer
,E/ActivityThread( 4218): Failed to find provider info for com.google.android.apps.docs.editors.trix.statesyncer
,E/ActivityThread( 4218): Failed to find provider info for com.google.android.apps.docs.editors.punch.statesyncer
,E/ActivityThread( 4218): Failed to find provider info for com.google.android.apps.docs.editors.drawings.statesyncer
,D/dalvikvm( 1019): GC_EXPLICIT freed 1284K, 65% free 17893K/50328K, paused 4ms+12ms, total 108ms
,D/WifiService( 1019): acquireWifiLockLocked: WifiLock{DocsSyncAdapter type=1 binder=android.os.BinderProxy@43d62ad0}
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4305 uid=10041 gids={50041, 3003}
,I/DownloadManager( 4089): Download 282 starting
,D/dalvikvm( 1373): GC_CONCURRENT freed 1931K, 28% free 12413K/17224K, paused 4ms+6ms, total 46ms
,I/GAV2    ( 3968): Thread[GAThread,5,main]: No campaign data found.
W/ActivityThread( 4089): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/PhoneMonitor( 4305): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4305): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1019): Killing 4060:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/DownloadManager( 4089): Download 283 starting
,I/CheckinService( 1373): Checkin interval check for package: unspecified last checkin: 1449862248998 min interval config: 0 actual interval: 238170591
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=4327 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
I/ContactAccountLoggerTas( 2168): canRun() : Opted Out
,I/Search.GservicesUpdateTask( 2168): Updating Gservices keys
,I/ActivityManager( 1019): Killing 4025:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinRequestBuilder( 1373): Classify the device as Phone.
,I/ContactAccountLoggerTas( 2168): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2168): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2168): canRun() : Opted Out
,I/CheckinTask( 1373): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/dalvikvm( 1993): GC_EXPLICIT freed 718K, 39% free 10654K/17224K, paused 2ms+18ms, total 59ms
,I/CheckinService( 1373): Checking schedule, now: 1450100419859 next: 1450693489777
,I/CheckinService( 1373): active receiver: disabled
,I/CheckinService( 1373): Checking schedule, now: 1450100419882 next: 1450693489777
,I/CheckinService( 1373): active receiver: disabled
,D/CheckinService( 1373): Recording last checkin time for package unspecified as 1450100419890
,I/ActivityManager( 1019): Killing 4037:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1373): Checkin interval check for package: unspecified last checkin: 1450100419890 min interval config: 0 actual interval: 40
,I/CheckinService( 1373): Checking schedule, now: 1450100419935 next: 1450693489777
,I/CheckinService( 1373): active receiver: disabled
,I/SystemUpdateService( 1373): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1373): onCreate
,D/SystemUpdateService( 1373): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 4327): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/SystemUpdateService( 1373): cancelUpdate (empty URL)
,I/SystemUpdateService( 1373): active receiver: disabled
,I/DownloadManager( 4089): Ignoring Content-Length since Transfer-Encoding is also defined
,I/Auth    ( 1993): [BroadcastManager] Broadcasting account services changed.
,I/iu.UploadsManager( 4327): End new media; added: 0, uploading: 0, time: 101 ms
,I/iu.Environment( 4327): update battery state; isPlugged? true*
I/iu.Environment( 4327): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.FingerprintManager( 4327): Start processing all media
,I/iu.FingerprintManager( 4327): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4327): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4327): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4327): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 4327): Finished generating fingerprints; 0.022 seconds
,I/iu.FingerprintManager( 4327):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/Checkin ( 4089): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,D/dalvikvm( 1993): GC_EXPLICIT freed 315K, 39% free 10624K/17224K, paused 2ms+6ms, total 39ms
,I/DownloadManager( 4089): Download 283 finished with status SUCCESS
,I/DownloadManager( 4089): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1373): GC_EXPLICIT freed 555K, 28% free 12419K/17224K, paused 4ms+6ms, total 45ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 582K, 65% free 17831K/50328K, paused 3ms+10ms, total 100ms
,D/Checkin ( 4089): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4089): Download 282 finished with status SUCCESS
,I/ActivityManager( 1019): Killing 3968:com.google.android.gm/u0a64 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/SystemUpdateService( 1373): onDestroy
,E/DynamiteModule( 1373): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1373): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1373): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1373): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1373): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1373): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1373): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1373): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1373): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1373): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1373): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1373): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/DynamiteModule( 1373): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/DynamiteModule( 1373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/DynamiteModule( 1373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1373): 	at android.os.Looper.loop(Looper.java:136)
E/DynamiteModule( 1373): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/DynamiteModule( 1373): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1373): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/DynamiteModule( 1373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/DynamiteModule( 1373): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1373): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1373): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 1373): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1373): Updating ocr activity enabled=false
,I/Auth    ( 1993): [BroadcastManager] Broadcasting account services changed.
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1373): Updating downloaded model state (gservices changed)
,D/GCM     ( 1993): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GAV2    ( 4218): DocsSyncAdapter-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 1019): releaseWifiLockLocked: WifiLock{DocsSyncAdapter type=1 binder=android.os.BinderProxy@43d62ad0}
,I/ActivityManager( 1019): Killing 3917:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PeopleSync( 1373): Sync finished, successful=true, took 2232ms
,I/ActivityManager( 1019): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4378 uid=10100 gids={50100, 3003, 1028, 1015, 3002}
,D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 1993): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,I/ActivityManager( 1019): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4390 uid=10057 gids={50057, 3003, 1028}
,D/dalvikvm( 1993): GC_EXPLICIT freed 314K, 39% free 10670K/17224K, paused 8ms+6ms, total 70ms
,E/dalvikvm( 1209): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1209): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/dalvikvm( 1209): VFY: replacing opcode 0x1f at 0x001a
,D/dalvikvm( 1209): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm( 1209): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
,W/dalvikvm( 1209): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1209): VFY: replacing opcode 0x6e at 0x0012
,V/com.google.android.apps.common.multidex.Tracer( 4390): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4390): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4390): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4390): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4390): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4390): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4390): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41f7e790, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41f7f500, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41f7f858]
,V/com.google.android.apps.common.multidex.Tracer( 4390): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41f7e790.
,I/GlobalDismissManager( 4004): no sender configured
,D/AlertService( 4004): Beginning updateAlertNotification
,V/com.google.android.apps.common.multidex.Tracer( 4390): Patching was successful.
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4404 uid=10008 gids={50008, 3003, 1028, 1015}
,I/PeopleSync( 1373): ***Sync canceled***, duration: 2737 [5005f081]
,D/SyncManager( 1019): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 222437, mTimeoutStartTime 222437, mHistoryRowId 14, syncOperation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, latestRunTime 28151, reason: Periodic
I/ActivityManager( 1019): Start proc com.google.android.apps.cloudprint for content provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider: pid=4419 uid=10057 gids={50057, 3003, 1028}
,I/CalendarProvider2( 4404): Created com.android.providers.calendar.CalendarAlarmManager@41f86070(com.android.providers.calendar.CalendarProvider2@41f7dc28)
,V/com.google.android.apps.common.multidex.Tracer( 4419): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4419): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4419): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4419): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4419): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4419): Package last updated: Jul 8, 2014 5:38:19.0
V/com.google.android.apps.common.multidex.Tracer( 4419): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41f837f0, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41f84560, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41f848b8]
,V/com.google.android.apps.common.multidex.Tracer( 4419): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41f837f0.
,V/com.google.android.apps.common.multidex.Tracer( 4419): Patching was successful.
,D/AlertService( 4004): No fired or scheduled alerts
,D/AlertService( 4004): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4004): No events found starting within 1 week.
,I/ActivityManager( 1019): Killing 4004:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/GCoreUlr( 1209): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1209): DispatchingService.onCreate()
,D/PlayMovies( 4378): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/GCM     ( 1993): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/dalvikvm( 1209): GC_CONCURRENT freed 2136K, 33% free 11582K/17224K, paused 4ms+10ms, total 52ms
,D/GCM     ( 1993): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MediaRouter( 4378): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ContactAccountLoggerTas( 2168): canRun() : Opted Out
,D/PlayMovies( 4378): MediaRouteManager.restoreRoute:197 sessionRestore routeId: 
,D/PlayMovies( 4378): MediaRouteManager.onRouteSelected:151 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 4378): TransferService.onCreate:52 creating transfer service
,W/ContextImpl( 4231): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/GCoreUlr( 1209): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/PlayMovies( 4378): MediaRouteManager.onRouteAdded:138 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 4378): MediaRouteManager.onRouteSelected:151 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4378): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.videos/files/Movies
I/openssl ( 4089): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4089): Crypto mode 0 already enabled
,W/ContextImpl( 4231): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,W/GeofencerStateMachine( 1209): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1209): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/DownloadManager( 4089): Download 284 starting
,W/ctxmgr  ( 1209): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10022, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1209): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/DownloadManager( 4089): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1993): GC_EXPLICIT freed 491K, 39% free 10653K/17224K, paused 5ms+5ms, total 37ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 1156K, 65% free 17916K/50328K, paused 5ms+11ms, total 102ms
,I/DownloadManager( 4089): Download 285 starting
,I/GCoreUlr( 1209): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1209): Unbound from all location providers
,I/GCoreUlr( 1209): Place inference reporting - stopped
,D/Checkin ( 4089): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4089): Ignoring Content-Length since Transfer-Encoding is also defined
,I/GCoreUlr( 1209): DispatchingService.onDestroy()
,I/GCoreUlr( 1209): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1209): Unbound from all location providers
,I/GCoreUlr( 1209): Place inference reporting - stopped
,I/DownloadManager( 4089): Download 284 finished with status SUCCESS
,W/ContextImpl( 4231): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4231): Update downloaded, starting installation
,I/UpdateFetcherService( 4231): Started installation
,I/PlayMovies( 4378): SyncService.syncAllPurchases:159 Starting sync for thalitester@gmail.com
,D/Checkin ( 4089): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4089): Download 285 finished with status SUCCESS
,D/DownloadManager( 4089): Download 285 already finished; skipping
,W/ContextImpl( 4231): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4231): Update downloaded, starting installation
,I/UpdateFetcherService( 4231): Started installation
,I/ConfigUpdateInstallReceiver( 1019): Not installing, new version is <= current version
I/openssl ( 4089): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4089): Crypto mode 0 already enabled
,I/CalendarProvider2( 4404): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4404): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4475 uid=10007 gids={50007, 3003}
,I/ActivityManager( 1019): Killing 4143:com.google.android.syncadapters.calendar/u0a65 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExtensionsFactory( 4475): No custom extensions.
,D/AlertReceiver( 4475): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4475): 0 Action = android.intent.action.PROVIDER_CHANGED
,I/PlayMovies( 4378): SyncService$3.onResponse:164 Sync completed for thalitester@gmail.com
I/ActivityManager( 1019): Killing 4271:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/BaseAppContext( 1209): Using Auth Proxy for data requests.
,E/BaseAppContext( 1209): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/ActivityManager( 1019): Killing 4177:android.process.acore/u0a10 (adj 15): empty #9
,I/ActivityManager( 1019): Killing 4305:com.google.android.setupwizard/u0a41 (adj 15): empty #10
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.apps.youtube.app.offline.sync.OfflineSyncService: pid=4515 uid=10102 gids={50102, 3003, 1028, 1015}
,D/YouTube ( 4515): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,D/dalvikvm( 1209): GC_EXPLICIT freed 1377K, 33% free 11629K/17224K, paused 3ms+6ms, total 45ms
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4515): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/cutils  (  263): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  263): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4515): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,I/GCoreUlr( 1209): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,D/YouTube ( 4515): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,I/GCoreUlr( 1209): DispatchingService.onCreate()
,D/YouTube ( 4515): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
I/ActivityManager( 1019): Killing 4327:com.google.android.apps.plus/u0a90 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/GCoreUlr( 1209): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1209): Unbound from all location providers
,I/GCoreUlr( 1209): Place inference reporting - stopped
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/YouTube ( 4515): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
I/GCoreUlr( 1209): DispatchingService.onDestroy()
I/GCoreUlr( 1209): Stopping handler for UlrDispSvcFast
,D/dalvikvm( 1993): GC_EXPLICIT freed 374K, 39% free 10632K/17224K, paused 5ms+5ms, total 38ms
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/YouTube ( 4515): apps.youtube.core.player.Director.c:360 VideoStage: NEW
,D/dalvikvm( 1019): GC_EXPLICIT freed 967K, 65% free 18065K/50328K, paused 5ms+11ms, total 107ms
I/GCoreUlr( 1209): Unbound from all location providers
,I/GCoreUlr( 1209): Place inference reporting - stopped
,I/MediaRouter( 4515): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/YouTube ( 4515): apps.youtube.core.client.s.a:114 event [version=5.6.36-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/GoogleConversionPing( 4515): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=OOR12PiaL5kcBDCoRWtvsQ&bundleid=com.google.android.youtube&appversion=5.6.36&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1450100423&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/YouTube ( 4515): apps.youtube.app.offline.sync.OfflineSyncService.onCreate:21 PUDL creating sync service for the 1st time
,W/YouTube ( 4515): apps.youtube.app.offline.sync.OfflineSyncService.onBind:28 PUDL binding sync adapter
,D/YouTube ( 4515): apps.youtube.common.d.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.h
D/YouTube ( 4515): apps.youtube.app.offline.sync.a.onPerformSync:60 OfflineSyncAdapter.onPerformSync() called!
,D/YouTube ( 4515): apps.youtube.datalib.offline.h.a:34 Network change detected, dispatch offline http requests.
,I/ActivityManager( 1019): Killing 4218:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,D/YouTube ( 4515): apps.youtube.common.d.j.e:170 Scheduling task com.google.android.apps.youtube.datalib.offline.o with ScheduledExecutorService for repeating execution.
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/GoogleConversionPing( 4515): Ping responded with response code 200
,D/dalvikvm( 1373): GC_EXPLICIT freed 1598K, 28% free 12508K/17224K, paused 4ms+10ms, total 48ms
,E/Auth.Api.Credentials( 1373): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1019): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4585 uid=10065 gids={50065, 3003}
,W/AbstractGoogleClient( 4585): Application name is not set. Call Builder#setApplicationName.
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4604 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/Launcher( 1284): Deferring update until onResume
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1284): Deferring update until onResume
,I/Launcher( 1284): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/Launcher( 1284): Deferring update until onResume
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
I/Babel   ( 4604): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4604): MmsConfig.loadMmsSettings
I/Babel   ( 4604): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
I/Babel   ( 4604): MmsConfig.loadFromDatabase
,E/Babel   ( 4604): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4604): MmsConfig.loadFromResources
,E/Babel   ( 4604): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4604): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
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
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
W/Settings( 4604): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4630 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/GCoreNlp( 1209): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4653 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4231:com.google.android.configupdater/u0a9 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2168): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4668 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1019): Killing 4089:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=4684 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ContactLocale( 4630): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4700 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4378:com.google.android.videos/u0a100 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/CalendarSyncAdapter( 4585): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2016-12-25T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,D/dalvikvm( 4684): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f7d950, skipping init
I/openssl ( 4684): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4684): Crypto mode 0 already enabled
,I/iu.UploadsManager( 4668): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/InternalIcingCorporaPro( 2168): UpdateCorporaTask done [took 309 ms] updated apps [took 309 ms] 
I/ActivityManager( 1019): Killing 4419:com.google.android.apps.cloudprint/u0a57 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 4390:com.google.android.apps.cloudprint:sync/u0a57 (adj 15): depends on provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider in dying proc com.google.android.apps.cloudprint
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4700): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4700): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x000e
,D/dalvikvm( 1019): GC_EXPLICIT freed 2050K, 64% free 18127K/50328K, paused 7ms+10ms, total 99ms
,D/CalendarSyncAdapter( 4585): Found 0 events marked dirty & lastSynced
,D/Finsky  ( 4700): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/iu.UploadsManager( 4668): End new media; added: 0, uploading: 0, time: 194 ms
,I/iu.Environment( 4668): update battery state; isPlugged? true*
I/iu.Environment( 4668): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.FingerprintManager( 4668): Start processing all media
,I/iu.FingerprintManager( 4668): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4668): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4668): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4668): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 4668): Finished generating fingerprints; 0.019 seconds
,I/iu.FingerprintManager( 4668):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
I/ActivityManager( 1019): Killing 4080:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 4700): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4700): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4700): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4700): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4700): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/dalvikvm( 4700): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4700): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4700): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4700): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4700): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4700): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4700): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4700): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4700): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4700): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4700): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4700): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4700): Skipping gmscore version check
,D/Finsky  ( 4700): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4700): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4700): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4700): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4700): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x0017
,D/PackageBroadcastService( 1373): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1373): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 4700): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1373): updateResources: need to parse f{com.google.android.gms}
,I/InternalIcingCorporaPro( 2168): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,I/ActivityManager( 1019): Killing 4515:com.google.android.youtube/u0a102 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1373): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
I/InternalIcingCorporaPro( 2168): UpdateCorporaTask done [took 40 ms] updated apps [took 40 ms] 
,V/AlarmManager( 1019): sending alarm Alarm{43d7daf0 type 0 com.android.vending}
,D/Finsky  ( 4700): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 4700): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4700): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4700): VFY: replacing opcode 0x62 at 0x0038
,I/Icing   ( 1373): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/Icing   ( 1373): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1373): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450100426
,I/qtaguid ( 4700): Failed write_ctrl(u 63) res=-1 errno=22
I/qtaguid ( 4700): Untagging socket 63 failed errno=-22
,W/NetworkManagementSocketTagger( 4700): untagSocket(63) failed with errno -22
,D/Finsky  ( 4700): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/dalvikvm( 4700): Total arena pages for JIT: 11
,I/dalvikvm( 4700): Total arena pages for JIT: 12
I/dalvikvm( 4700): Total arena pages for JIT: 13
,I/dalvikvm( 4700): Total arena pages for JIT: 14
,I/qtaguid ( 4700): Failed write_ctrl(u 63) res=-1 errno=22
I/qtaguid ( 4700): Untagging socket 63 failed errno=-22
,W/NetworkManagementSocketTagger( 4700): untagSocket(63) failed with errno -22
,I/GlobalDismissManager( 4475): no sender configured
,D/AlertService( 4475): Beginning updateAlertNotification
,D/AlertService( 4475): No fired or scheduled alerts
,D/AlertService( 4475): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4475): No events found starting within 1 week.
,D/dalvikvm( 4700): GC_CONCURRENT freed 4817K, 29% free 12299K/17224K, paused 2ms+3ms, total 36ms
,D/dalvikvm( 4700): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm( 4700): GC_CONCURRENT freed 1275K, 25% free 13071K/17224K, paused 1ms+4ms, total 30ms
,D/dalvikvm( 4700): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4700): GC_CONCURRENT freed 852K, 18% free 14267K/17224K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 4700): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4700): GC_CONCURRENT freed 974K, 11% free 15340K/17224K, paused 1ms+2ms, total 44ms
,D/dalvikvm( 4700): WAIT_FOR_CONCURRENT_GC blocked 33ms
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1993): GC_EXPLICIT freed 338K, 39% free 10625K/17224K, paused 2ms+5ms, total 32ms
,I/qtaguid ( 4700): Failed write_ctrl(u 63) res=-1 errno=22
,I/qtaguid ( 4700): Untagging socket 63 failed errno=-22
,W/NetworkManagementSocketTagger( 4700): untagSocket(63) failed with errno -22
,D/Finsky  ( 4700): [1] LibraryUtils.isAvailable: com.quickoffice.android available because owned, overriding [restriction=7].
,D/Finsky  ( 4700): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4700): [1] DailyHygiene.access$600: Logging device features
,D/dalvikvm( 4700): GC_CONCURRENT freed 2199K, 14% free 15186K/17488K, paused 2ms+2ms, total 65ms
,D/dalvikvm( 4700): WAIT_FOR_CONCURRENT_GC blocked 47ms
,D/dalvikvm( 4700): WAIT_FOR_CONCURRENT_GC blocked 46ms
,V/AlarmManager( 1019): sending alarm Alarm{427f6260 type 0 com.android.vending}
,D/DeviceConnectionService( 1209): client connected with version: 8296000
,D/Finsky  ( 4700): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/Finsky  ( 4700): [403] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4700): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1373): GC_CONCURRENT freed 1972K, 28% free 12457K/17224K, paused 3ms+4ms, total 36ms
,I/ActivityManager( 1019): Killing 4475:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/PackageSettings( 1019): Skipping PackageSetting{4224a6f8 com.example.hello/10442} due to missing metadata
,V/AlarmManager( 1019): sending alarm Alarm{43d7d220 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{426a67f8 type 0 com.android.vending}
,I/PeopleSync( 1373): onPerformSync() [5005f081]
,I/PeopleSync( 1373): Setting subscription: result=true [5005f081]
,D/Finsky  ( 4700): [393] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4700): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/IcingInternalCorpora( 1373): getNumBytesRead when not calculated.
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43343138 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{433431f8 type 2 android}
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 49056 ms ago
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4843 uid=10059 gids={50059, 3003, 1028, 1015}
,E/ActivityThread( 1373): Failed to find provider info for com.android.contacts.metadata
D/SyncManager( 1019): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 278102, reason: UserStart
,W/ActiveOrDefaultContextProvider( 4843): Missing scope.enter somewhere. Returning default context
,W/GAV2    ( 4843): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 4843): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1019): Killing 4604:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/GAV2    ( 4843): Thread[GAThread,5,main]: No campaign data found.
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{422b3cc8 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c7cad0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/ClearcutLoggerApiImpl( 1373): disconnect managed GoogleApiClient
,I/ClearcutLoggerApiImpl( 1993): disconnect managed GoogleApiClient
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427bf8d8 type 3 android}
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 8 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 9 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 10
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 10
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3559): Connected to the server!
I/jxcore-log( 3559): 
,I/chromium( 3559): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1019): sending alarm Alarm{427ec390 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4347b338 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427bf998 type 1 com.android.deskclock}
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4896 uid=10015 gids={50015, 1028}
,D/dalvikvm( 1019): GC_EXPLICIT freed 1524K, 65% free 18115K/50328K, paused 4ms+9ms, total 99ms
,I/ActivityManager( 1019): Killing 4404:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43ca2f08 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d7d220 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d7b120 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427bfa70 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{427bfc70 type 0 com.google.android.gms}
,I/EventLogService( 1373): Aggregate from 1450100413990 (log), 1450098901124 (data)
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
,I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d05cb0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4210f578 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43ced008 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4278a288 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
,I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4238e770 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{44043570 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = ,
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open '',
,V/AlarmManager( 1019): sending alarm Alarm{4207e208 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
,I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427b3870 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43ceb110 type 2 com.google.android.gms}
,I/GCM     ( 1373): Message from null null
,E/GCM     ( 1373): Dropping message from null,
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1082): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1270): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1082): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1270): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1270): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1082): updateTelephonySignalStrength:  No service
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427f40b8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d524d0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4278c380 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d665d0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{427d8390 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427eabd0 type 1 com.android.deskclock}
,V/AlarmManager( 1019): sending alarm Alarm{42196cf8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4403c410 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43a3aef0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
,I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4347ac80 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
,I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d7b228 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d5e190 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42e42e68 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 21ms
,I/ProcessStatsService( 1019): Prepared write state in 26ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-13-12-07-00.bin
,V/AlarmManager( 1019): sending alarm Alarm{427de7a0 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{427cb978 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427cb9c8 type 3 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1993): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{446d2d00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42146698 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43deca10 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5070): 
D/AndroidRuntime( 5070): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5070): CheckJNI is OFF
D/dalvikvm( 5070): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5070): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5070): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5070): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5070): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 5070): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 5070): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 5070): failed to load memtrack module: -2
D/AndroidRuntime( 5070): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10467 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3559:com.test.thalitest/u0a467 (adj 9): stop com.test.thalitest
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{447988c8 u0 com.test.thalitest/.MainActivity t3}
I/WindowState( 1019): WIN DEATH: Window{445e6ee0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1019): Client connection lost with reason: 4
W/PackageSettings( 1019): Skipping PackageSetting{4224a6f8 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10467 user=0: pkg removed
D/dalvikvm( 1373): GC_EXPLICIT freed 677K, 28% free 12462K/17224K, paused 3ms+6ms, total 45ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450102210
I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 2168): GC_EXPLICIT freed 4765K, 42% free 10149K/17224K, paused 2ms+7ms, total 128ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
W/GeofencerStateMachine( 1209): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 2136): GC_EXPLICIT freed 6391K, 44% free 9746K/17224K, paused 2ms+19ms, total 117ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/dalvikvm( 1284): GC_EXPLICIT freed 2955K, 33% free 11631K/17224K, paused 2ms+32ms, total 145ms
D/VoicemailCleanupService( 4630): Cleaning up data for package: com.test.thalitest
I/Launcher( 1284): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
D/dalvikvm( 1019): GC_EXPLICIT freed 2015K, 64% free 18331K/50328K, paused 6ms+17ms, total 172ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 100ms
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
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2168): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5101 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/Launcher( 1284): Deferring update until onResume
I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450102210
W/ContextImpl( 5101): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10467 #1
I/dalvikvm( 4700): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4700): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4700): VFY: replacing opcode 0x6e at 0x0013
I/InternalIcingCorporaPro( 2168): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
D/PackageBroadcastService( 1373): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1373): Clearing selected account for com.test.thalitest
D/dalvikvm( 1019): GC_EXPLICIT freed 531K, 64% free 18249K/50328K, paused 7ms+15ms, total 188ms
D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1373): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager( 1019): Killing 4585:com.google.android.syncadapters.calendar/u0a65 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/NetworkScheduler.SchedulerReceiver( 1993): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1993): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5126 uid=10058 gids={50058}
I/Icing   ( 1373): doRemovePackageData com.test.thalitest
V/AlarmManager( 1019): sending alarm Alarm{43d57ec0 type 3 com.google.android.gms}
D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1373): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/Documents( 5126): Loading roots for com.android.providers.downloads.documents
D/AndroidRuntime( 5070): Shutting down VM
D/dalvikvm( 5070): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
D/Documents( 5126): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5144 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1019): Killing 4896:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019): Killing 4630:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1225): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 5144): After updating volumes, found 1 active roots
D/Documents( 5126): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 5126): Loading roots for com.android.providers.media.documents
D/Documents( 5126): Loading roots for com.google.android.apps.docs.storage
D/Documents( 5126): Update found 7 roots in 138ms
D/Documents( 5126): Used cached roots for com.android.providers.downloads.documents
D/Documents( 5126): Loading roots for com.android.externalstorage.documents
D/Documents( 5126): Used cached roots for com.android.providers.media.documents
D/Documents( 5126): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 5126): Update found 7 roots in 6ms

```
