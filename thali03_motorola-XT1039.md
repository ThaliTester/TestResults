#### Test 5105326159f447b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{4401c228 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3592): 
D/AndroidRuntime( 3592): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3592): CheckJNI is OFF
D/dalvikvm( 3592): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3592): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3592): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3592): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3592): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3592): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3592): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3592): failed to load memtrack module: -2
D/AndroidRuntime( 3592): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3592
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3608 uid=10379 gids={50379, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3592): Shutting down VM
D/dalvikvm( 3592): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 25ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 24ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
V/WebViewChromiumFactoryProvider( 3608): Binding Chromium to main looper Looper (main, tid 1) {41fd69b8}
I/LibraryLoader( 3608): Expected native library version number "",actual native library version number ""
I/chromium( 3608): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3608): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43908998:true
D/BluetoothAdapter( 3608): 1107210184: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3608): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3608): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3608): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3608): Local Branch: 
I/Adreno-EGL( 3608): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3608): Local Patches: NONE
I/Adreno-EGL( 3608): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3608): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3608): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3608): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3608): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3608): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3608): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3608): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3608): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3608): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3608): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3608): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3608): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3608): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3608): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3608): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3608): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3608): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3608): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3608): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3608): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3608): Enabling debug mode 0
,W/AwContents( 3608): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3608): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,414
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +386ms (total +414ms)
,D/JsMessageQueue( 3608): Set native->JS mode to OnlineEventsBridgeMode
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 3608): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdae68
,D/dalvikvm( 3608): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdae68
,D/jxcore_app_log( 3608): JniHelper::setJavaVM(0x41622fa8), pthread_self() = 1614143256
,D/JX-Cordova( 3608): jxcore cordova android initializing
I/dalvikvm( 3608): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 3608): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3608): VFY: replacing opcode 0x6e at 0x0045
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
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
,D/dalvikvm( 3608): GC_CONCURRENT freed 2985K, 18% free 14204K/17224K, paused 3ms+3ms, total 38ms
,D/dalvikvm( 3608): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3608): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 3608): GC_FOR_ALLOC freed 143K, 18% free 14167K/17224K, paused 24ms, total 24ms
,D/dalvikvm( 3608): GC_FOR_ALLOC freed 256K, 18% free 14217K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3608): Grow heap (frag case) to 16.126MB for 220492-byte allocation
,D/dalvikvm( 3608): GC_FOR_ALLOC freed 376K, 19% free 14293K/17440K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3608): Grow heap (frag case) to 16.306MB for 330734-byte allocation
,D/dalvikvm( 3608): GC_FOR_ALLOC freed 584K, 19% free 14418K/17764K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3608): Grow heap (frag case) to 16.585MB for 496096-byte allocation
,D/dalvikvm( 3608): GC_FOR_ALLOC freed 885K, 21% free 14596K/18252K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3608): Grow heap (frag case) to 16.996MB for 744140-byte allocation
,D/dalvikvm( 3608): GC_FOR_ALLOC freed 1310K, 22% free 14857K/18980K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3608): Grow heap (frag case) to 17.606MB for 1116206-byte allocation
,D/dalvikvm( 3608): GC_CONCURRENT freed 1709K, 25% free 15246K/20072K, paused 1ms+4ms, total 43ms
,D/dalvikvm( 3608): GC_CONCURRENT freed 1576K, 22% free 15751K/20072K, paused 2ms+3ms, total 36ms
,D/dalvikvm( 3608): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 3608): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 3608): GC_FOR_ALLOC freed 1883K, 21% free 15911K/20072K, paused 31ms, total 33ms
,I/dalvikvm-heap( 3608): Grow heap (frag case) to 19.965MB for 2511452-byte allocation
,D/dalvikvm( 3608): GC_CONCURRENT freed 248K, 19% free 18292K/22528K, paused 5ms+5ms, total 57ms
,D/dalvikvm( 3608): GC_CONCURRENT freed 4511K, 26% free 16838K/22528K, paused 1ms+10ms, total 57ms
,D/dalvikvm( 3608): WAIT_FOR_CONCURRENT_GC blocked 49ms
,I/dalvikvm-heap( 3608): Grow heap (frag case) to 22.068MB for 3767174-byte allocation
,D/dalvikvm( 3608): GC_CONCURRENT freed 2838K, 32% free 17870K/26208K, paused 1ms+5ms, total 47ms
,W/jxcore-log( 3608): Initializing JXcore engine
,W/jxcore-log( 3608): JXcore engine is ready
,D/dalvikvm( 3608): GC_CONCURRENT freed 483K, 23% free 20343K/26208K, paused 1ms+3ms, total 29ms
,D/dalvikvm( 3608): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3608): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 3608): Starting JXcore engine
,W/jxcore-log( 3608): Platform android
W/jxcore-log( 3608): 
,W/jxcore-log( 3608): Process ARCH arm
W/jxcore-log( 3608): 
,I/jxcore-log( 3608): JXcore Cordova bridge is ready!
I/jxcore-log( 3608): 
,W/jxcore-log( 3608): JXcore engine is started
,I/chromium( 3608): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3608): Turning radios to true
I/jxcore-log( 3608): 
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): enable():  mBluetooth =null mBinding = false
,W/Settings( 1230): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
D/BluetoothManagerService( 1019): Message: 1
D/BluetoothManagerService( 1019): MESSAGE_ENABLE: mBluetooth = null
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
,D/WifiService( 1019): New client listening to asynchronous messages
,W/XTWiFiOS( 1259): Active network info is not available
D/WifiService( 1019): setWifiEnabled: true pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3670 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/Settings( 1230): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiStateMachine( 1019): setting operational mode to 1
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,W/Settings( 1230): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/Settings( 1230): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1259): Active network info is not available
,D/AdapterServiceConfig( 3670): Adding HeadsetService
D/AdapterServiceConfig( 3670): Adding A2dpService
D/AdapterServiceConfig( 3670): Adding HidService
D/AdapterServiceConfig( 3670): Adding HealthService
D/AdapterServiceConfig( 3670): Adding PanService
D/AdapterServiceConfig( 3670): Adding GattService
,D/AdapterServiceConfig( 3670): Adding BluetoothMapService
D/BluetoothAdapterService( 3670): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@434ed190:true
,D/BluetoothAdapterState( 3670): make
,I/bluedroid( 3670): init
,I/BluetoothAdapterState( 3670): Entering OffState
,I/bte_conf( 3670): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3670): get_profile_interface socket
I/GKI_LINUX( 3670): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1019): Message: 40
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3670): config_hci_snoop_log
D/BluetoothAdapterProperties( 3670): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1019): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterProperties( 3670): Name is: XT1039
,D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
D/BluetoothAdapterState( 3670): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3670): Setting state to 11
I/BluetoothAdapterState( 3670): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3670): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothBondStateMachine( 3670): make
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3670): StableState(): Entering Off State
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3706 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/BluetoothHeadset( 1019): Proxy object connected
,D/BluetoothHeadset( 1247): Proxy object connected
,D/BluetoothHeadset( 1247): Proxy object connected
D/HeadsetService( 3670): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3670): classInitNative: succeeds
D/HeadsetStateMachine( 3670): Version 1.6
,D/HeadsetStateMachine( 3670): make
,D/BluetoothHeadset( 1247): Proxy object connected
,I/BluetoothAdapterState( 3670): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3670): get_profile_interface handsfree
,D/BluetoothA2dp( 1019): Proxy object connected
,D/A2dpService( 3670): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3670): classInitNative: succeeds
V/Avrcp   ( 3670): make
,I/bluedroid( 3670): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3670): classInitNative: succeeds
D/A2dpStateMachine( 3670): make
,I/bluedroid( 3670): get_profile_interface a2dp
,I/GKI_LINUX( 3670): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3670): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3670): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3670): classInitNative: succeeds
,D/HidService( 3670): Received start request. Starting profile...
I/bluedroid( 3670): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3670): classInitNative: succeeds
,D/HealthService( 3670): Received start request. Starting profile...
,I/bluedroid( 3670): get_profile_interface health
,I/BluetoothPanServiceJni( 3670): classInitNative(L105): succeeds
,D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
D/PanService( 3670): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3670): initializeNative(L110): pan
,I/bluedroid( 3670): get_profile_interface pan
D/BluetoothTethering( 1019): got CMD_CHANNEL_HALF_CONNECTED
I/BtGatt.JNI( 3670): classInitNative(L684): classInitNative: Success!
,D/BluetoothTethering( 1019): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@433172e8
,D/BtGatt.DebugUtils( 3670): handleDebugAction() action=null
D/BtGatt.GattService( 3670): Received start request. Starting profile...
D/BtGatt.GattService( 3670): start()
,I/bluedroid( 3670): get_profile_interface gatt
,D/BluetoothMapService( 3670): Received start request. Starting profile...
,D/BluetoothMapService( 3670): start()
,D/HeadsetPhoneState( 3670): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3670): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3670): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3670): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3670): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3670): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3670): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/HeadsetPhoneState( 3670): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3670): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3670): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3670): enable
,I/bt_hci_bdroid( 3670): init
I/bt_vendor( 3670): bt-vendor : init
I/bt_hci_bdroid( 3670): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3670): userial_init
I/bt_hwcfg( 3670): Starting hciattach daemon
I/bt_hwcfg( 3670): try to set false
I/bt_hci_bdroid( 3670): bt_hc_worker_thread started
I/bt_hwcfg( 3670): Starting hciattach daemon
,I/bt_hwcfg( 3670): try to set true
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
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,I/qcom-bluetooth( 3731): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
D/TCMD    (  449): NL - Read 1004 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
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
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  449): NL - Read 1004 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/QsoftapCmd(  271): Got softap fwreload command we are passing on
,D/SoftapController(  271): Softap fwReload - Ok
,D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring down wlan0
,I/qcom-bluetooth( 3741): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 3742): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,I/ActivityManager( 1019): Killing 3438:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/qcom-bluetooth( 3744): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/qcom-bluetooth( 3745): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,I/qcom-bluetooth( 3746): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/Diag_Lib( 3750): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3750): Setting internal use port to rmnet0
E/Diag_Lib( 3750):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3750): Failed on DIAG init
E/Diag_Lib( 3750): linux_qmi_qmux_if_client_get_proc_name: pid=3750, proc_name=hci_qcomm_init
E/Diag_Lib( 3750): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3750): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3750): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3750): qmi_client [3750]: successfully connected to server, attempt=1
E/Diag_Lib( 3750): linux_qmi_qmux_if_client_get_client_id [3750]: qmux_client_id=13
E/Diag_Lib( 3750): qmi_client [3750] 13: qmux_client ID is initialized
E/Diag_Lib( 3750): qmi_client [3750] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3750): qmi_client [3750] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3750): qmi_client [3750] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3750): Sending signal ...... to read cmd data 
E/Diag_Lib( 3750): qmi error code.........:0
E/Diag_Lib( 3750): qmi sys error code.........:0
E/Diag_Lib( 3750): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3750): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3750): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3750): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3750): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3750): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3750): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3750): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3750): qmi_init:  Created client handle b7d8c788
,E/Diag_Lib( 3750): qmi_client [3750] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3750): qmi_client [3750] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3750): Sending signal ...... to read cmd data 
E/Diag_Lib( 3750): qmi error code.........:0
,E/Diag_Lib( 3750): qmi sys error code.........:0
E/Diag_Lib( 3750): Setting the api flag to : 1
,E/Diag_Lib( 3750): qmi_client [3750] 13: sending 54 bytes on fd = 8
,I/wpa_supplicant( 3748): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3748): rfkill: Cannot open RFKILL control device
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1019): setWifiState: enabling
,E/Diag_Lib( 3748): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3748): Setting internal use port to rmnet0
,D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,E/wpa_supplicant( 3748): baseband property is set to [msm]
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1259): Active network info is not available
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
I/rmt_storage(  428): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb890f1d0
I/rmt_storage(  428): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  428): wakelock acquired: 1, error no: 42
,I/rmt_storage(  428): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1198460360)
E/Diag_Lib( 3750): qmi_client [3750] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3750):  API Flag .............. 1 
,E/Diag_Lib( 3750):  Message ID ............... 92 
,E/wpa_supplicant( 3748):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3748): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3748): card_info[i].card_state: 0x2
E/wpa_supplicant( 3748): card_info[i].error_code: 0x3
E/wpa_supplicant( 3748): SIM/USIM not ready
,E/wpa_supplicant( 3748): Error while reading SIM card status
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
E/wpa_supplicant( 3748): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3748): card_info[i].card_state: 0x2
E/wpa_supplicant( 3748): card_info[i].error_code: 0x3
E/wpa_supplicant( 3748): SIM/USIM not ready
,I/wpa_supplicant( 3748): eap_proxy: Card not ready
,E/Diag_Lib( 3750): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3750): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3750): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3750): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3750): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3750): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3750): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3750): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3750): qmi_client [3750] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3750): qmi_client [3750] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3750): Sending signal ...... to read cmd data 
E/Diag_Lib( 3750): qmi error code.........:0
E/Diag_Lib( 3750): qmi sys error code.........:0
E/Diag_Lib( 3750): qmi_release: Released client handle ff
E/Diag_Lib( 3750): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3750): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3750): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3750): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3750): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3750): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3750): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3750): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3750): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3750): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3750): qmi_client [3750] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3750): qmi_client [3750] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3750): Sending signal ...... to read cmd data 
E/Diag_Lib( 3750): qmi error code.........:0
E/Diag_Lib( 3750): qmi sys error code.........:0
E/Diag_Lib( 3750): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3750] 13
E/Diag_Lib( 3750): qmi_client [3750] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3750): qmi_client [3750] 13: failed to locate client data
E/Diag_Lib( 3750): qmi_client [3750] 13: calling release of fd=8
,E/Diag_Lib( 3750): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,D/dalvikvm( 1019): GC_EXPLICIT freed 21747K, 64% free 17872K/49616K, paused 4ms+11ms, total 206ms
D/WifiService( 1019): New client listening to asynchronous messages
,I/rmt_storage(  428): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  428): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  428): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1198460360) wakelock released: 1, error no: 0
I/rmt_storage(  428): 
,I/rmt_storage(  428): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb890f1d0
,I/wpa_supplicant( 3748): Long line in configuration file truncated
,V/BluetoothFtpReceiver( 3670): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1360): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 3748): rfkill: Cannot open RFKILL control device
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,I/qcom-bluetooth( 3755): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3756): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/wpa_supplicant( 3748): COUNTRY Code Recived
E/wpa_supplicant( 3748): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3748): baseband property is set to [msm]
,E/wpa_supplicant( 3748):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3748): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3748): card_info[i].card_state: 0x2
E/wpa_supplicant( 3748): card_info[i].error_code: 0x3
E/wpa_supplicant( 3748): SIM/USIM not ready
,E/wpa_supplicant( 3748): Error while reading SIM card status
E/wpa_supplicant( 3748): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3748): card_info[i].card_state: 0x2
E/wpa_supplicant( 3748): card_info[i].error_code: 0x3
E/wpa_supplicant( 3748): SIM/USIM not ready
,I/wpa_supplicant( 3748): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
,D/WifiStateMachine( 1019): invokeExitMethods: InitialState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartingState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131144
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): deferMessage: msg=131085
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131149
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
I/bt_hwcfg( 3670): bluetooth satus is on
D/WifiStateMachine( 1019): setSuspendOptimizations: 2 true
D/bt_userial_mct( 3670): userial_open(port:0)
,D/WifiStateMachine( 1019): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1019): handleMessage: X
I/bt_userial_vendor( 3670): Done intiailizing UART
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
I/bt_userial_vendor( 3670): Done intiailizing UART
D/WifiStateMachine( 1019): processMsg: DefaultState
I/bt_userial_mct( 3670): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3670): Bluetooth Firmware and smd is initialized
,D/bt_userial_mct( 3670): Entering userial_read_thread()
I/GKI_LINUX( 3670): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
D/WifiStateMachine( 1019): handleMessage: X
I/bt-btu  ( 3670): btu_task pending for preload complete event
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
D/WifiStateMachine( 1019): setWifiState: enabled
,I/bt-btu  ( 3670): btu_task received preload complete event
,W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1259): Active network info is not available
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiConfigStore( 1019): Loading config and enabling all networks
I/        ( 3670): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3670): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3670): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3670): BTE_InitTraceLevels -- TRC_AVDT
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
I/        ( 3670): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3670): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3670): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3670): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3670): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3670): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3670): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3670): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3670): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3670): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3670): BTE_InitTraceLevels -- TRC_BTIF
E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
E/wpa_supplicant( 3748): COUNTRY Code Recived -COUNTRY PL
D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3748): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3748): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
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
,E/bt-btm  ( 3670): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f163049 
,E/bt-btm  ( 3670): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f163049 
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131144
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131085
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/CommandListener(  271): Setting iface cfg
,D/CommandListener(  271): Trying to bring up p2p0
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131152
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
E/bt-btif ( 3670): Calling BTA_HhEnable
D/WifiStateMachine( 1019): set country code PL
,E/bt-btif ( 3670): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:2 len:6
D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/BluetoothAdapterProperties( 3670): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:1 len:6
D/WifiP2pService( 1019): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/BluetoothAdapterProperties( 3670): Name is: XT1039
,D/WifiP2pService( 1019): P2pEnabledState
I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3670): Scan Mode:21
I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3670): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:8 len:6
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
E/wpa_supplicant( 3748): COUNTRY Code Recived
E/wpa_supplicant( 3748): COUNTRY Code Recived
D/BluetoothAdapterProperties( 3670): Adding bonded device:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:3 len:48
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
E/BluetoothRemoteDevices( 3670): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set frequency band 2
I/bte_conf( 3670): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3670): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3670): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3670): hci lib postload completed
I/bte_conf( 3670): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothPanServiceJni( 3670): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 3670): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3670): ScanMode =  21
D/BluetoothAdapterProperties( 3670): State =  11
D/BluetoothAdapterProperties( 3670): Setting state to 12
I/BluetoothAdapterState( 3670): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3670): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 3670): Entering On State
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1107154512)( 3670): Get Bonded Devices being called
D/BluetoothPan( 1019): onBluetoothStateChange on: true
D/BluetoothAdapterProperties( 3670): getBondedDevices: length=1
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3670): Discoverable Timeout:120
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService( 1019): Message: 40
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
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
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiStateMachine( 1019): processMsg: DefaultState
D/BluetoothMapService( 3670): onReceive
D/BluetoothMapService( 3670): STATE_ON
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiP2pService( 1019): MCC mode enabled 0
D/BluetoothMapService( 3670): Map Service startRfcommSocketListener
D/BluetoothAdapterService(1107154512)( 3670): Get Bonded Devices being called
D/BluetoothAdapterService(1107154512)( 3670): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3670): getBondedDevices: length=1
D/BluetoothAdapterProperties( 3670): getBondedDevices: length=1
,D/BluetoothMapService( 3670): Map Service initSocket
,D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-39ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-39ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-42ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-42ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3748): COUNTRY Code Recived
E/wpa_supplicant( 3748): COUNTRY Code Recived
,I/qcom-bt-wlan-coex( 3771): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
D/WifiP2pService( 1019): InactiveState{ when=-13ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-14ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(1107154512)( 3670): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3670): getBondedDevices: length=1
W/BluetoothAdapter( 3670): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3670): SOCK FLAG = 1 ***********************
D/BluetoothMapService( 3670): Accepting socket connection...
I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3670): Scan Mode:21
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424aed80:true
,D/BluetoothPbapService( 3670): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3670): Handler(): got msg=1
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/LocalBluetoothProfileManager( 3706): Adding local A2DP profile
,D/BluetoothManagerService( 1019): Message: 30
,W/BluetoothAdapter( 3670): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
E/BluetoothServiceJni( 3670): SOCK FLAG = 1 ***********************
D/LocalBluetoothProfileManager( 3706): Adding local HEADSET profile
D/BluetoothAdapterService(1107154512)( 3670): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3670): getBondedDevices: length=1
,D/BluetoothManagerService( 1019): Message: 30
W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3706): Adding local MAP profile
D/BluetoothMap( 3706): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3706): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3706): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3706): finishStartingService: stopping service
,D/BluetoothAdapterService(1107154512)( 3670): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3670): getBondedDevices: length=1
,D/BluetoothA2dp( 3706): Proxy object connected
,D/A2dpProfile( 3706): Bluetooth service connected
,D/BluetoothHeadset( 3706): Proxy object connected
,D/HeadsetProfile( 3706): Bluetooth service connected
,D/BluetoothInputDevice( 3706): Proxy object connected
,D/HidProfile( 3706): Bluetooth service connected
,D/BluetoothPan( 3706): BluetoothPAN Proxy object connected
D/PanProfile( 3706): Bluetooth service connected
,D/BluetoothMap( 3706): Proxy object connected
,D/MapProfile( 3706): Bluetooth service connected
,D/BluetoothMap( 3706): getConnectedDevices()
D/BluetoothPbap( 3706): Proxy object connected
,D/PbapServerProfile( 3706): Bluetooth service connected
,V/BluetoothFtpReceiver( 3670): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3670): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1360): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3670): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3670): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3670): Accept thread started.
V/BluetoothFtpService( 3670): Ftp Service onCreate
I/BluetoothFtpService( 3670): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3670): Starting FTP service
V/BluetoothFtpService( 3670): Ftp Service onStartCommand
,V/BluetoothFtpService( 3670): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3670): Handler(): got msg=1
V/BluetoothFtpService( 3670): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3670): Ftp Service initSocket
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3670): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3670): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3670): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3670): Run Accept thread
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/MDMCTBK (  274): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  274): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): wifi_connect_to_supplicant, current pid is = 274
D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  274): wifi_close_sockets: Exit
,E/MDMCTBK (  274): Attach monitor thread
I/MDMCTBK (  274): createWifiMonitorThread: Started the wifi monitor thread -1197390920
,D/MDMCTBK (  274): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,I/wpa_supplicant( 3748): wlan0: Trying to associate with SSID 'NG700'
I/wpa_supplicant( 3747): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 3747): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,E/wpa_supplicant( 3748): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 64:7c:34:b0:03:6e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 64:7c:34:b0:03:6e
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  274): Event received = Trying to associate with
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  449): NL - Read 312 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 88 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
I/wpa_supplicant( 3748): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3748): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,I/wpa_supplicant( 3748): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  449): NL - Read 80 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 80 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3748): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3748): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
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
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1197395256
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE ,
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-29ms what=147462 obj=android.net.wifi.StateChangeResult@424e4ba8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4224de58 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4224de58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  449): NL - Read 56 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 06
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 10
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 10
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43cef228 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@43cef228 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-5ms what=147462 obj=android.net.wifi.StateChangeResult@43cef228 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  449): NL - Read 60 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 20
,D/TCMD    (  449): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3608): Attempting to connect to the test coordinator server
I/jxcore-log( 3608): 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=0 what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): DHCP successful
D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.123
D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=151572
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1019): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine( 1019): CaptivePortalCheckState enter
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
D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@421d12a0
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
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
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1264): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1264): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1264): onReceive() - done, currentInetCondition=0
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@421d12a0
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1264): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1264): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1264): onReceive() - done, currentInetCondition=0
,W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/        ( 1019): Setting time of day to sec=1447838173
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/        ( 1019): Unable to set rtc to 1447838173: Invalid argument
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/PollingManager( 1534): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/PollingManager( 1534): now: 319499 ,futureTime: 86439340
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/PollingManager( 1534): Polling alarm set to expire at: 86439340 Current Time: 319505
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/openssl ( 3054): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3054): Crypto mode 0 already enabled
,E/ActivityThread( 1534): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1534): registerApp(): CCE
I/CCE     ( 1534): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1534): Registering with Alarm Manager to restart CCE
,D/PollingManager( 1534): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PollingManager( 1534): now: 319571 ,futureTime: 86439340
,D/PollingManager( 1534): Polling alarm set to expire at: 86439340 Current Time: 319571
,E/ActivityThread( 1534): Failed to find provider info for com.motorola.blur.setupprovider
D/MMApiWebService( 1534): Received data connectivity intent from PollingManager .. retry the waiting requests: 3
D/CCE     ( 1534): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1534): isRequestAllowed(): already have outstanding request ... ignoring request
D/CCE     ( 1534): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1534): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1534): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1534): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1534): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1534): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/MMApiWebService( 1534): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiWebService( 1534): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1534): generating token using payload instead of using session token
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/MMApiWSBase( 1534): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
D/OtaApp  ( 1534): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/MMApiWSBase( 1534): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1534): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3868 uid=10030 gids={50030, 3003, 1028, 1015}
,V/MmsConfig( 3868): mnc/mcc: 
,V/MmsConfig( 3868): tag: bool value: enabledMMS - true
,V/MmsConfig( 3868): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3868): tag: int value: maxImageHeight - 1944
,V/MmsConfig( 3868): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3868): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3868): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3868): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3868): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3868): tag: int value: recipientLimit - 20
,V/MmsConfig( 3868): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3868): tag: int value: smsToMmsTextThreshold - 6
,V/MmsConfig( 3868): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3868): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3868): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 3868): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3868): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 3868): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3868): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/VacuumService( 1360): Vacuum at: now=1447838173833 tag=VacuumService
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3890 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3460:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3902 uid=10056 gids={50056, 3003, 1028, 1015}
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,D/MobileConnectivityChangeReceiver( 3890): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3890): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3890): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3890): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager( 1019): Killing 3136:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1347): Checkin interval check for package: unspecified last checkin: 1447785919012 min interval config: 0 actual interval: 52254949
,I/CheckinService( 1347): Checking schedule, now: 1447838173968 next: 1447785948971
,I/CheckinService( 1347): active receiver: enabled
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,I/CheckinService( 1347): Preparing to send checkin request
I/EventLogService( 1347): Accumulating logs since 1447836768349
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1247): GC_EXPLICIT freed 1391K, 45% free 9515K/17224K, paused 4ms+22ms, total 80ms
,D/TelephonyProvider( 1247): Column apn id key is 'apn_id'
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3918 uid=10076 gids={50076, 3003, 1028, 1015}
,I/dalvikvm( 1347): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 1347): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1347): VFY: replacing opcode 0x6e at 0x0033
,I/GoogleURLConnFactory( 1347): Using platform SSLCertificateSocketFactory
,D/DelayedSyncController( 3902): Delaying sync.
,D/GpsLocationProvider( 1019): NTP server returned: 1447838170570 (Wed Nov 18 10:16:10 CET 2015) reference: 316526 certainty: 16 system time offset: -3550
,E/LocSvc_ApiV02( 1019): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,I/ActivityManager( 1019): Killing 3488:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 3918): Binding Chromium to main looper Looper (main, tid 1) {41fd18b8}
,I/LibraryLoader( 3918): Expected native library version number "",actual native library version number ""
,I/chromium( 3918): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3918): Initializing chromium process, renderers=0
,D/dalvikvm( 1019): GC_EXPLICIT freed 1830K, 64% free 17887K/49616K, paused 4ms+18ms, total 117ms
,E/AudioManagerAndroid( 3918): BLUETOOTH permission is missing!
,E/Auth.Api.Credentials( 1347): [CredentialSyncAdapter] Unknown sync event.
,I/Adreno-EGL( 3918): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3918): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3918): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3918): Local Branch: 
I/Adreno-EGL( 3918): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3918): Local Patches: NONE
I/Adreno-EGL( 3918): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 3918): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3918): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 1534): GC_CONCURRENT freed 2907K, 38% free 10784K/17224K, paused 4ms+2ms, total 33ms
,I/CheckinRequestBuilder( 1347): Checkin reason type: 8 attempt count: 1
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3918): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/WifiService( 1019): New client listening to asynchronous messages
,E/ActivityThread( 1347): Failed to find provider info for com.google.android.wearable.settings
,D/DelayedSyncController( 3902): Delaying sync.
,I/ActivityManager( 1019): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3970 uid=10064 gids={50064, 3003, 1028, 1015}
,I/NSApplication( 3918): Starting up...
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ImageResourceManager( 3515): ImageResourceManager: uninitalized
,I/iu.Environment( 3515): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ActivityThread( 3970): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
I/iu.SyncManager( 3515): SYNC; picasa accounts
,I/ActivityManager( 1019): Killing 3115:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3515): num queued entries: 0
,I/iu.UploadsManager( 3515): num updated entries: 0
,I/iu.SyncManager( 3515): NEXT; no task
,I/iu.SyncManager( 1347): SYNC; picasa accounts
,D/NetworkLogImpl( 1347): Loaded NetworkSpeedPredictor
,W/GAV2    ( 3970): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/iu.Environment( 1347): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1347): num queued entries: 0
,I/iu.UploadsManager( 1347): num updated entries: 0
,I/iu.SyncManager( 1347): NEXT; no task
,D/dalvikvm( 1360): GC_EXPLICIT freed 1172K, 39% free 10555K/17224K, paused 10ms+5ms, total 44ms
,I/openssl ( 3054): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3054): Crypto mode 0 already enabled
,I/MMApiWSBase( 1534): doRequest(): error in response: 403
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1534): doRequest(): error in response: {"error":"INVALID_SESSION","error_text":"Please provide a valid authtoken"}
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 1534): doRequest(): v1/ns/list/messages resp length: 75
,I/MMApiWebService( 1534): _inspectMMApiResponse(): found an error from a web service response: ForbiddenError msg: INVALID_SESSION req: 
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/MobileConnectivityChangeReceiver( 3890): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3890): onReceive CONNECTIVITY_CHANGE networkType=1
,I/MMApiWebService( 1534): _inspectMMApiResponse(): received invalid session error from the server.. need to re-login
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 1347): GC_CONCURRENT freed 1565K, 34% free 11522K/17224K, paused 4ms+22ms, total 89ms
,I/iu.Environment( 3515): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/MMApiProvisionService( 1534): Got request to obtain new Session .. doing so now
,D/MMApiProvisionService( 1534): isRequestAllowed(): already have outstanding request ... ignoring request
,I/MMApiWebService( 1534): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 1534): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"172742","deviceId":"1135300315450105856"}
I/dalvikvm( 1360): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 1360): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1360): VFY: replacing opcode 0x6e at 0x0033
,D/MMApiProvisionService( 1534): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1534): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1534): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiWebService( 1534): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiProvisionService( 1534): handleResponse(): Session Expiration alarm set to expire at: Fri Nov 20 10:15:16 CET 2015
,D/MMApiProvisionService( 1534): _setMMApiCredInfo: storing credential info 
,D/DEBUG   ( 1534): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1534): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/MMApiWSBase( 1534): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/check.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=1
,E/MMApiProvisionService( 1534): handleResponse(): no settings sent by the server:
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,D/EmailService.MarketingOptInSetter( 1534): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/MMApiWebService( 1534): MMApiWebService told us to retry waiting request since device is successfully provisioned: 1
,D/MMApiWebService( 1534): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1534): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4010 uid=10007 gids={50007, 3003}
,I/Gmail   ( 3970): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3970): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ExtensionsFactory( 4010): No custom extensions.
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=4030 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 3172:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4037 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3706:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiService( 1019): Client connection lost with reason: 4
I/Gmail   ( 3970): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3970): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/CalendarProvider2( 4037): Created com.android.providers.calendar.CalendarAlarmManager@41feeda0(com.android.providers.calendar.CalendarProvider2@41fe6958)
,I/GCM     ( 1360): GCM config loaded
,V/AlarmClock( 4030): AlarmInitReceiver android.intent.action.TIME_SET
,I/Gmail   ( 3970): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 10663, normalSync: true
,I/AlarmClock( 4030): Displaying next alarm time: ''
,V/AlarmClock( 4030): AlarmInitReceiver finished
,D/UdcCache:FPQuery( 1347): Bootstrapping UDC settings cache for all accounts
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4066 uid=10098 gids={50098}
,D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 889K, 64% free 17887K/49616K, paused 5ms+13ms, total 106ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 3ms+3ms, total 22ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,D/dalvikvm( 4066): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41fdae60, skipping init
D/TimeService( 4066): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1447838175419
D/        ( 4066): TimeServiceNative: User Time to be set is 1447838175419
D/QC-time-services( 4066): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4066): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4066): Lib:time_genoff_operation: pargs->ts_val = 1447838175419
,D/QC-time-services(  418): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 4066): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  418): Daemon:Received base = 2, unit = 1, operation = 0,value = 1447838175419
D/QC-time-services(  418): Daemon:genoff_opr: Base = 2, val = 1447838175419, operation = 0
D/QC-time-services(  418): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/18/115 9:10:26
D/QC-time-services(  418): Daemon:Value read from RTC seconds = 1447837826000
D/QC-time-services(  418): Daemon:new time 1447838175419 
D/QC-time-services(  418): Daemon: delta 349419 genoff 349419 
D/QC-time-services(  418): Daemon:genoff_persistent_update: Writing genoff = 349419 to memory
D/QC-time-services(  418): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  418): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  418): Updating the TOD offset
D/QC-time-services(  418): Daemon:genoff_persistent_update: Writing genoff = 349419 to memory
D/QC-time-services(  418): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  418): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  418): Daemon:Update to modem bit set
D/QC-time-services(  418): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  418): Daemon: Base = 2, Value being sent to MODEM = 18446743757745101035
,E/QC-time-services( 4066): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager( 1019): Killing 3054:android.process.media/u0a18 (adj 15): empty #9
E/QC-time-services(  418): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  418): Daemon: Time-services: Waiting to acceptconnection
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1347): Checkin interval check for package: unspecified last checkin: 1447785919012 min interval config: 0 actual interval: 52256451
,D/DEBUG   ( 1534): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1534): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1534): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1534): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1534): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1534
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1534): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1534
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,107
D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/DEBUG   ( 1534): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SundryService( 1534): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1534): Received shoulder tap
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{4204a588 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/WaitableIntentService( 1534): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,D/GetNotificationsWS( 1534): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1534): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=2
,D/dalvikvm( 1360): GC_CONCURRENT freed 1928K, 39% free 10624K/17224K, paused 31ms+5ms, total 113ms
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1264): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1264): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1264): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1264): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/GetConfigurationSnapshotOperation( 1360): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/MMApiWSBase( 1534): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1534): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1534): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1534): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1534): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1534): Received intent : com.motorola.ccc.notification.action.NOTIFY
,I/SundryService( 1534): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1534): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 1534): onHandleIntent(): isWaitEnabled=true
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=1
,I/PhenotypeFlagCommitter( 1360): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/MMApiWebService( 1534): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1534): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,I/ActivityManager( 1019): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4090 uid=10065 gids={50065, 3003}
D/Checkin ( 1534): publish the event [tag = MOT_CCE event name = LOG]
,I/GoogleURLConnFactory( 1360): Using platform SSLCertificateSocketFactory
,W/AbstractGoogleClient( 4090): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4104 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 4104): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4104): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4104): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4104): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 4104): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4104): install
,I/MultiDex( 4104): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 4104): loading existing secondary dex files
,I/MultiDex( 4104): load found 3 secondary dex files
,I/MultiDex( 4104): install done
,D/GetCommittedConfigurationOperation( 1360): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 4104): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4104): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4104): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4104): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4104): VFY: unable to resolve instance field 46
,D/dalvikvm( 4104): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4104): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4104): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4104): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4104): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4104): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 4104): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fd2da8
D/dalvikvm( 4104): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fd2da8
,D/dalvikvm( 4104): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fd2da8, skipping init
,D/dalvikvm( 4104): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fd2da8
D/dalvikvm( 4104): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fd2da8
,V/JNIHelp ( 4104): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 4104): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41fd2da8
,D/dalvikvm( 4104): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41fd2da8
D/dalvikvm( 4104): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41fd2da8
,D/dalvikvm( 4104): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fd2da8
,I/CalendarProvider2( 4037): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4037): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4010): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4010): 0 Action = android.intent.action.PROVIDER_CHANGED
,I/ProviderInstaller( 4104): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1207): callingUid 10022, callindPid: 1207
,E/MDM     ( 1207): [72] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1347): Restart initialization of location
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/dalvikvm( 4104): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 4104): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x000d
,D/AuthorizationBluetoothService( 1360): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1360): Proximity feature is not enabled.
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 4104): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 4104): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x0220
,V/GmsCoreStatsServiceLauncher( 1347): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 4104): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4104): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 4104): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 4104): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
,D/dalvikvm( 4104): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4104): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 4104): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4104): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4104): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 4104): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,D/MMApiWSBase( 1534): doRequest(): v1/us/devices/check resp length: 188
,D/CCE     ( 1534): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1534): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.-2081052800 for reqID:  error: None
,D/OtaWebService( 1534): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@42772490 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@42157818
,D/OtaWebService( 1534): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"pollAfterSeconds\":86400,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"No upgrade found for this device at this time.\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1534): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@42773b30 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@42157818
,D/OtaWebService( 1534): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"pollAfterSeconds\":86400,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"No upgrade found for this device at this time.\\\"}\"}\n","errorText":""}}
,I/OtaApp  ( 1534): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update : 200 :  
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,W/GCoreFlp( 1207): No location to return for getLastLocation()
,W/FusedLocationProvider( 1360): location=null
,I/OtaApp  ( 1534): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: no upgrades found for this device at this time
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > CusAndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
,I/OtaApp  ( 1534): [info] > Next Polling is scheduled at 1439 mins from now
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/PollingManager( 1534): registerApp(): cUsPollingService
,D/OtaApp  ( 1534): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
,D/OtaApp  ( 1534): [debug] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: authoritative response from BOTA ERR_NOTFOUND
,D/MMApiWSBase( 1534): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1534): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/CCE     ( 1534): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1534): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): Level3 Library Nov 20 2013 18:09:31
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1534): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
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
,D/OtaApp  ( 1534): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1534): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1534): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1534
,D/OtaWebService( 1534): [debug] > appending web service response to serviceHandler
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaWebService( 1534): [debug] > Removing request :v1/us/devices/check from queue
,D/OtaWebService( 1534): [debug] > No pending web request. shutdown webservice
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1534): [info] > Updatetime from metadata: 10
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/Checkin ( 1534): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
D/OtaApp  ( 1534): [debug] > cancelling the previous pending intent set for install later
,D/SundryService( 1534): handleGetNotificationsResponse(): got 0; more=false
,I/OtaApp  ( 1534): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaWebService( 1534): [info] > Stopping webservice android service
,D/Checkin ( 1534): publish the event [tag = MOT_OTA event name = LOG]
,D/DEBUG   ( 1534): Received intent : com.motorola.ccc.notification.action.NOTIFY
,D/OtaApp  ( 1534): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SundryService( 1534): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1534): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1534): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1534): ServiceHandler.handleMessage: mWaitCount=0
,D/QSEECOMAPI: (  279): Loaded image: APP id = 3
D/DrmWidevineDash(  279): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53c1000
E/DrmWidevineDash(  279): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb53c1000
I/dalvikvm( 4104): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 4104): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x0033
,D/GetNotificationsWS( 1534): unbindWebServices(): un-registering our AIDL callback...
,W/dalvikvm( 4104): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4104): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 4104): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/DrmWidevineDash(  279): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_APIVersion...
I/dalvikvm( 4104): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4104): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x00bb
D/DrmWidevineDash(  279): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  279): calling OEMCrypto_IsKeyboxValid...
,I/GoogleURLConnFactory( 4104): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  279): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  279): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
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
,D/GetCommittedConfigurationOperation( 1360): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=3649149432
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/NativeLibraryUtils( 4104): Install completed successfully. count=13 extracted=0
,W/Uploader( 1360):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1360): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,D/GetCommittedConfigurationOperation( 1360): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1360): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1360): GC_CONCURRENT freed 1543K, 36% free 11045K/17224K, paused 4ms+6ms, total 36ms
,D/dalvikvm( 4104): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42373ff0
D/dalvikvm( 4104): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42373ff0
,D/dalvikvm( 4104): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42373ff0, skipping init
,D/dalvikvm( 4104): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4139): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4104): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4104): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 99ms
,I/Adreno-EGL( 4104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4104): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4104): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4104): Local Branch: 
I/Adreno-EGL( 4104): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4104): Local Patches: NONE
I/Adreno-EGL( 4104): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/CalendarSyncAdapter( 4090): Found 0 events marked dirty & lastSynced
,I/Adreno-EGL( 4104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4104): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4104): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4104): Local Branch: 
I/Adreno-EGL( 4104): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4104): Local Patches: NONE
I/Adreno-EGL( 4104): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/ActivityManager( 1019): Killing 3868:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=4143 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/DrmWidevineDash(  279): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  279): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  279): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetRandom...
D/DrmWidevineDash(  279): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  279): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  279): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  279): PrepareKeyRequest: nonce=3712787865
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  279): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 3970): GC_EXPLICIT freed 5134K, 44% free 9740K/17224K, paused 2ms+4ms, total 50ms
,I/Gmail   ( 3970): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 10728, normalSync: true
,I/Gmail   ( 3970): lowestBackward conversation id 0
,I/ContactLocale( 4143): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager( 1019): Killing 3890:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/DrmWidevineDash(  279): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  279): CdmEngine::CloseSession
,D/DrmWidevineDash(  279): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  279): OEMCrypto_CloseSession returns 0
,I/PeopleSync( 1347): onPerformSync() [5005f081]
,I/PeopleDatabaseHelper( 1347): cleanUpNonGplusAccounts done.
,D/dalvikvm( 1019): GC_EXPLICIT freed 1284K, 65% free 17807K/49616K, paused 4ms+9ms, total 97ms
,I/PeopleSync( 1347): Setting subscription: result=true [5005f081]
I/PeopleSync( 1347): Starting sync, feed=null [5005f081]
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,W/Settings( 4104): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,I/PeopleSync( 1347): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/Adreno-EGL( 4104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4104): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4104): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4104): Local Branch: 
I/Adreno-EGL( 4104): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4104): Local Patches: NONE
I/Adreno-EGL( 4104): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4104): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4104): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4104): Local Branch: 
I/Adreno-EGL( 4104): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4104): Local Patches: NONE
I/Adreno-EGL( 4104): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1347): Classify the device as Phone.
,I/ActivityManager( 1019): Killing 3902:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,D/dalvikvm( 1347): GC_CONCURRENT freed 1998K, 33% free 11599K/17224K, paused 4ms+4ms, total 45ms
,W/SQLiteConnectionPool( 1347): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/CheckinTask( 1347): Sending checkin request (11837 bytes)
,D/dalvikvm( 1360): GC_EXPLICIT freed 1498K, 37% free 10946K/17224K, paused 3ms+5ms, total 36ms
,W/BaseAppContext( 1347): Using Auth Proxy for data requests.
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4179 uid=10059 gids={50059, 3003, 1028, 1015}
,I/CheckinRequestBuilder( 1347): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1347): Failed to find provider info for com.google.android.wearable.settings
,W/ActiveOrDefaultContextProvider( 4179): Missing scope.enter somewhere. Returning default context
,W/GAV2    ( 4179): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/ActivityThread( 4179): Failed to find provider info for com.google.android.apps.docs.editors.kix.statesyncer
,E/ActivityThread( 4179): Failed to find provider info for com.google.android.apps.docs.editors.trix.statesyncer
,E/ActivityThread( 4179): Failed to find provider info for com.google.android.apps.docs.editors.punch.statesyncer
,E/ActivityThread( 4179): Failed to find provider info for com.google.android.apps.docs.editors.drawings.statesyncer
,D/WifiService( 1019): acquireWifiLockLocked: WifiLock{DocsSyncAdapter type=1 binder=android.os.BinderProxy@43d7b910}
,I/CheckinRequestBuilder( 1347): Classify the device as Phone.
,I/CheckinTask( 1347): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1347): Checking schedule, now: 1447838179331 next: 1448431249317
,I/CheckinService( 1347): active receiver: disabled
,D/CheckinService( 1347): Recording last checkin time for package unspecified as 1447838179351
,I/GAV2    ( 3918): Thread[GAThread,5,main]: No campaign data found.
,D/GCM     ( 1360): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 3970): Thread[GAThread,5,main]: No campaign data found.
,I/PeopleSync( 1347): Sync finished, successful=true, took 1427ms
,I/PeopleSync( 1347): ***Sync finished***, duration: 1919 [5005f081]
,I/ActivityManager( 1019): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4231 uid=10100 gids={50100, 3003, 1028, 1015, 3002}
,D/PlayMovies( 4231): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,I/MediaRouter( 4231): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 4231): MediaRouteManager.restoreRoute:197 sessionRestore routeId: 
,D/PlayMovies( 4231): MediaRouteManager.onRouteSelected:151 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/PlayMovies( 4231): TransferService.onCreate:52 creating transfer service
,D/PlayMovies( 4231): MediaRouteManager.onRouteAdded:138 new route added android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE
,D/PlayMovies( 4231): MediaRouteManager.onRouteSelected:151 routeInfo: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4231): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.videos/files/Movies
,D/dalvikvm( 1019): GC_EXPLICIT freed 958K, 65% free 17836K/49616K, paused 4ms+10ms, total 92ms
,W/GAV2    ( 4179): DocsSyncAdapter-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 1019): releaseWifiLockLocked: WifiLock{DocsSyncAdapter type=1 binder=android.os.BinderProxy@43d7b910}
I/ActivityManager( 1019): Killing 3515:com.google.android.apps.plus/u0a90 (adj 15): empty #9
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4274 uid=10057 gids={50057, 3003, 1028}
,V/com.google.android.apps.common.multidex.Tracer( 4274): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4274): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4274): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4274): Checking if extracted archive /data/data/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4274): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4274): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4274): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41fe46b8, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41fe5428, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41fe5780]
,V/com.google.android.apps.common.multidex.Tracer( 4274): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41fe46b8.
,V/com.google.android.apps.common.multidex.Tracer( 4274): Patching was successful.
,I/ActivityManager( 1019): Start proc com.google.android.apps.cloudprint for content provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider: pid=4287 uid=10057 gids={50057, 3003, 1028}
,V/com.google.android.apps.common.multidex.Tracer( 4287): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary0.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4287): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4287): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4287): Checking if extracted archive /data/user/0/com.google.android.apps.cloudprint/files/secondary1.zip is up to date.
V/com.google.android.apps.common.multidex.Tracer( 4287): Extracted file last modified: Aug 24, 2015 8:20:50.0
V/com.google.android.apps.common.multidex.Tracer( 4287): Package last updated: Jul 8, 2014 5:38:19.0
,V/com.google.android.apps.common.multidex.Tracer( 4287): Attempting to patch the classloader using the following patchers [com.google.android.apps.common.multidex.KlpClassLoaderExtender@41fe8880, com.google.android.apps.common.multidex.IcsClassLoaderExtender@41fe95f0, com.google.android.apps.common.multidex.PreIcsClassLoaderExtender@41fe9948]
,V/com.google.android.apps.common.multidex.Tracer( 4287): Trying com.google.android.apps.common.multidex.KlpClassLoaderExtender@41fe8880.
,V/com.google.android.apps.common.multidex.Tracer( 4287): Patching was successful.
,I/PlayMovies( 4231): SyncService.syncAllPurchases:159 Starting sync for thalitester@gmail.com
,I/GlobalDismissManager( 4010): no sender configured
,D/AlertService( 4010): Beginning updateAlertNotification
,D/AlertService( 4010): No fired or scheduled alerts
,D/AlertService( 4010): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4010): No events found starting within 1 week.
I/ActivityManager( 1019): Killing 4066:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PlayMovies( 4231): SyncService$3.onResponse:164 Sync completed for thalitester@gmail.com
,I/ActivityManager( 1019): Killing 4030:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1207): GC_EXPLICIT freed 1472K, 41% free 10275K/17224K, paused 2ms+5ms, total 33ms
,E/DataBuffer( 1207): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42196d40)
,I/dalvikvm( 1207): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 1207): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1207): VFY: replacing opcode 0x6e at 0x0033
,D/dalvikvm( 1360): GC_EXPLICIT freed 922K, 37% free 10917K/17224K, paused 2ms+6ms, total 40ms
,W/BaseAppContext( 1207): Using Auth Proxy for data requests.
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1207): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1207): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1207): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1207): VFY: replacing opcode 0x6e at 0x00bb
,I/ActivityManager( 1019): Killing 4010:com.android.calendar/u0a7 (adj 15): empty #9
,I/ActivityManager( 1019): Killing 4037:com.android.providers.calendar/u0a8 (adj 15): empty #10
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.apps.youtube.app.offline.sync.OfflineSyncService: pid=4324 uid=10102 gids={50102, 3003, 1028, 1015}
,D/YouTube ( 4324): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4324): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4324): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,D/YouTube ( 4324): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,D/YouTube ( 4324): apps.youtube.common.network.l.a:40 HttpClient.UserAgent: com.google.android.youtube/5.6.36(Linux; U; Android 4.4.4; en_GB; XT1039 Build/KXB21.14-L1.46)
,D/dalvikvm( 1360): null clazz in OP_INSTANCE_OF, single-stepping
,D/YouTube ( 4324): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 4324): apps.youtube.core.player.Director.c:360 VideoStage: NEW
,I/GCoreUlr( 1207): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1207): DispatchingService.onCreate()
,I/MediaRouter( 4324): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/YouTube ( 4324): apps.youtube.core.client.s.a:114 event [version=5.6.36-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 4324): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=OOR12PiaL5kcBDCoRWtvsQ&bundleid=com.google.android.youtube&appversion=5.6.36&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1447838182&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/YouTube ( 4324): apps.youtube.app.offline.sync.OfflineSyncService.onCreate:21 PUDL creating sync service for the 1st time
,W/YouTube ( 4324): apps.youtube.app.offline.sync.OfflineSyncService.onBind:28 PUDL binding sync adapter
,D/YouTube ( 4324): apps.youtube.common.d.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.h
,D/YouTube ( 4324): apps.youtube.datalib.offline.h.a:34 Network change detected, dispatch offline http requests.
,I/GCoreUlr( 1207): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/YouTube ( 4324): apps.youtube.app.offline.sync.a.onPerformSync:60 OfflineSyncAdapter.onPerformSync() called!
,I/GCoreUlr( 1207): Unbound from all location providers
,I/ActivityManager( 1019): Killing 4090:com.google.android.syncadapters.calendar/u0a65 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/YouTube ( 4324): apps.youtube.common.d.j.e:170 Scheduling task com.google.android.apps.youtube.datalib.offline.o with ScheduledExecutorService for repeating execution.
,I/GCoreUlr( 1207): DispatchingService.onDestroy()
,I/GCoreUlr( 1207): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1207): Unbound from all location providers
,D/dalvikvm( 1347): GC_CONCURRENT freed 1912K, 33% free 11654K/17224K, paused 13ms+5ms, total 50ms
,E/Auth.Api.Credentials( 1347): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager( 1019): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=4392 uid=10065 gids={50065, 3003}
,I/GoogleConversionPing( 4324): Ping responded with response code 200
,D/dalvikvm( 1360): GC_EXPLICIT freed 555K, 37% free 10901K/17224K, paused 3ms+5ms, total 34ms
,W/AbstractGoogleClient( 4392): Application name is not set. Call Builder#setApplicationName.
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4407 uid=10008 gids={50008, 3003, 1028, 1015}
,I/CalendarProvider2( 4407): Created com.android.providers.calendar.CalendarAlarmManager@41feef08(com.android.providers.calendar.CalendarProvider2@41fe6ac0)
,D/dalvikvm( 1019): GC_EXPLICIT freed 851K, 65% free 17845K/49616K, paused 4ms+10ms, total 90ms
,I/ActivityManager( 1019): Killing 3970:com.google.android.gm/u0a64 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.78/generate_204
W/ActivityThread( 1019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,V/CalendarSyncAdapter( 4392): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2016-11-25T00:00:00.000Z, updatedMin=2015-11-05T21:58:54.693Z}
,D/CalendarSyncAdapter( 4392): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 1019): Killing 3918:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4433 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
I/Launcher( 1286): Deferring update until onResume
I/CalendarProvider2( 4407): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4407): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 23ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1286): Deferring update until onResume
,I/ActivityManager( 1019): Killing 4143:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 20ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/Launcher( 1286): Deferring update until onResume
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
,I/Launcher( 1286): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/GAV2    ( 4179): Thread[GAThread,5,main]: No campaign data found.
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
,I/Babel   ( 4433): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4433): MmsConfig.loadMmsSettings
I/Babel   ( 4433): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4433): MmsConfig.loadFromDatabase
,E/Babel   ( 4433): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4433): MmsConfig.loadFromResources
E/Babel   ( 4433): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4433): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4433): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/GmsNetworkLocationProvi( 1207): DISABLE
,I/GCoreNlp( 1207): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4462 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 4179:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4480 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4231:com.google.android.videos/u0a100 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2198): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4497 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1019): Killing 4287:com.google.android.apps.cloudprint/u0a57 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 4274:com.google.android.apps.cloudprint:sync/u0a57 (adj 15): depends on provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider in dying proc com.google.android.apps.cloudprint
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4462): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=4515 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4529 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4324:com.google.android.youtube/u0a102 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 4497): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/dalvikvm( 4515): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fd8038, skipping init
I/openssl ( 4515): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4515): Crypto mode 0 already enabled
,I/dalvikvm( 4529): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4529): VFY: unable to resolve virtual method 616: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x000d
,D/Finsky  ( 4529): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/InternalIcingCorporaPro( 2198): UpdateCorporaTask done [took 349 ms] updated apps [took 349 ms] 
,I/dalvikvm( 4529): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4529): VFY: unable to resolve virtual method 547: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x01d3
,I/iu.UploadsManager( 4497): End new media; added: 0, uploading: 0, time: 150 ms
,I/iu.Environment( 4497): update battery state; isPlugged? true*
,I/iu.Environment( 4497): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.FingerprintManager( 4497): Start processing all media
,I/iu.FingerprintManager( 4497): Start processing media store URI: content://media/external/images/media
,I/dalvikvm( 4529): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4529): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x000a
,I/iu.FingerprintManager( 4497): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 4497): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4497): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 4497): Finished generating fingerprints; 0.024 seconds
,I/iu.FingerprintManager( 4497):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/Finsky  ( 4529): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 4529): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4529): VFY: unable to resolve virtual method 337: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4529): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4529): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4529): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4529): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4529): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4529): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x0392
I/dalvikvm( 4529): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4529): VFY: unable to resolve virtual method 20701: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x0398
,D/dalvikvm( 1019): GC_CONCURRENT freed 1926K, 64% free 18010K/49616K, paused 4ms+9ms, total 84ms
,I/dalvikvm( 4529): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 4529): VFY: unable to resolve virtual method 8983: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4529): Skipping gmscore version check
,D/Finsky  ( 4529): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4529): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4529): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4529): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4529): VFY: unable to resolve virtual method 612: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4529): VFY: replacing opcode 0x6e at 0x0017
,D/PackageBroadcastService( 1347): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1347): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 4529): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1347): updateResources: need to parse f{com.google.android.gms}
,I/InternalIcingCorporaPro( 2198): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
I/ActivityManager( 1019): Killing 4407:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1347): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4583 uid=10007 gids={50007, 3003}
,I/PeopleContactsSync( 1347): CP2 sync disabled
,I/InternalIcingCorporaPro( 2198): UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
,D/ExtensionsFactory( 4583): No custom extensions.
,D/AlertReceiver( 4583): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4583): 0 Action = android.intent.action.PROVIDER_CHANGED
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4605 uid=10008 gids={50008, 3003, 1028, 1015}
,I/CalendarProvider2( 4605): Created com.android.providers.calendar.CalendarAlarmManager@41febe70(com.android.providers.calendar.CalendarProvider2@41fe3a28)
,I/CalendarProvider2( 4605): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4605): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4583): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/ActivityManager( 1019): Killing 4104:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 3608): Attempting to connect to the test coordinator server
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Attempting to connect to the test coordinator server
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Attempting to connect to the test coordinator server
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Attempting to connect to the test coordinator server
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Attempting to connect to the test coordinator server
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Attempting to connect to the test coordinator server
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Test app app.js loaded
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): {"type":"test","name":"setup","id":0}
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): LogCallback not set !!!!
I/jxcore-log( 3608): 
,W/IInputConnectionWrapper( 3608): showStatusIcon on inactive InputConnection
,I/chromium( 3608): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3608): DBG, CoordinatorConnector connect called
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): DBG, CoordinatorConnector connect called
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): DBG, CoordinatorConnector connect called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector connect called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector connect called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector connect called
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): DBG, CoordinatorConnector connect called
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":0,"type":"assert"}
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@434dd2a0 mBinding = false
,D/BluetoothManagerService( 1019): Message: 2
W/Settings( 1230): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
D/BluetoothManagerService( 1019): Sending off request.
D/BluetoothAdapterState( 3670): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3670): Setting state to 13
I/BluetoothAdapterState( 3670): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3670): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 3670): onBluetoothDisable()
I/BluetoothAdapterState( 3670): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 3670): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3670): Scan Mode:21
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothAdapterState( 3670): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
E/bt-btif ( 3670): bta_jv_rfcomm_stop_server
E/bt-btif ( 3670): bta_jv_rfcomm_stop_server
E/bt-btif ( 3670): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 3670): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3670): bta_jv_rfcomm_stop_server
V/BluetoothFtpService:RfcommSocketAcceptThread( 3670): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothMapService( 3670): onReceive
W/bt-btif ( 3670): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/BluetoothMapService( 3670): STATE_TURNING_OFF removeTimeoutMsg:false
D/BluetoothMapService( 3670): MAP Service closeService in
W/Settings( 1230): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/bt-l2cap( 3670): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3670): L2CAP - PSM: 0x0017 not found for deregistration
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/btif_config_util( 3670): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4639 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/Settings( 1230): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/Settings( 1230): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/BtOppRfcommListener( 3670): stopping Accept Thread
I/BtOppRfcommListener( 3670): BluetoothSocket listen thread finished
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/TCMD    (  449): NL - Read 60 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 21
D/TCMD    (  449): Listening for incoming client connection request
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiMetrics( 1019): connected time updated 17241
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/ConnectivityService( 1019): resetConnections(wlan0, 3)
,D/NetUtils( 1019): android_net_utils_resetConnections in env=0x61256108 clazz=0x66700001 iface=wlan0 mask=0x3
D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
D/WifiP2pService( 1019): P2pDisablingState
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiP2pService( 1019): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
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
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131205
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
I/jxcore-log( 3608): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartedState
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
V/NativeCrypto( 1360): Read error: ssl=0x611edd80: I/O error during system call, Connection timed out
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
V/NativeCrypto( 1360): SSL shutdown failed: ssl=0x611edd80: I/O error during system call, Broken pipe
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/CommandListener(  271): Clearing all IP addresses on wlan0
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): stopping supplicant
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): setWifiState: disabling
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1019): handleMessage: X
W/XTWiFiOS( 1259): Active network info is not available
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
E/XTCC-3.0.0.2(  575): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  575): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  575): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  575): [CSMgr] handleConnectivtyStatusChange failed
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
,I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/ModemStatsDSDetect( 1264): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1264): INET_CONDITION=0 ,activeNet=null
D/ConnectivityService( 1019): Attempting to switch to mobile
,I/ModemStatsDSDetect( 1264): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
I/ModemStatsDSDetect( 1264): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/bt_hwcfg( 3670): hw_epilog_process
W/bt-btif ( 3670): ag scb idx 1 not allocated
I/wpa_supplicant( 3748): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/bt-btif ( 3670): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3670): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3670): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3670): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3670): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3670): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3670): L2CAP - PSM: 0x0017 not found for deregistration
I/ModemStatsDSDetect( 1264): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1264): onReceive() - done, currentInetCondition=0
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
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
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
D/Tethering( 1019): InitialState.processMessage what=4
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
D/TCMD    (  449): NL - Read 68 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
I/wpa_supplicant( 3748): eap_proxy Deinitialzed
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7
D/BluetoothPbapService( 3670): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): Message: 20
I/bt_hwcfg( 3670): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 3670): bt_hc_worker_thread exiting
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4289b938:true
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
D/bt_userial_mct( 3670): userial_close
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/bt_userial_mct( 3670): exiting userial_read_thread
D/bt_userial_mct( 3670): Leaving userial_evt_read_thread()
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): Message: 30
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3608): 
W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService( 1019): Message: 30
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/LocalBluetoothProfileManager( 4639): Adding local MAP profile
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothMap( 4639): Create BluetoothMap proxy object
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): Message: 30
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothManagerService( 1019): Message: 30
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4639): LocalBluetoothProfileManager construction complete
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
D/TCMD    (  449): Listening for incoming client connection request
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
I/wpa_supplicant( 3748): wlan0: CTRL-EVENT-TERMINATING 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  274):  Wpa Supplicant Exiting !!
D/MDMCTBK (  274): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  274): wifi_close_sockets: Exit
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): Supplicant connection lost
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
D/DockEventReceiver( 4639): finishStartingService: stopping service
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/WifiService( 1019): New client listening to asynchronous messages
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothInputDevice( 4639): Proxy object connected
D/HidProfile( 4639): Bluetooth service connected
D/BluetoothPan( 4639): BluetoothPAN Proxy object connected
D/PanProfile( 4639): Bluetooth service connected
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
D/BluetoothMap( 4639): Proxy object connected
I/jxcore-log( 3608): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/MapProfile( 4639): Bluetooth service connected
D/BluetoothMap( 4639): getConnectedDevices()
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
V/BluetoothFtpReceiver( 3670): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMap( 4639): Bluetooth is Not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/ActivityManager( 1019): Killing 4392:com.google.android.syncadapters.calendar/u0a65 (adj 15): empty #9
D/AuthorizationBluetoothService( 1360): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/BTSNOOP-DISP( 3670): btsnoop_close
I/bt_vendor( 3670): cleanup
I/bt_hwcfg( 3670): Starting hciattach daemon
I/bt_hwcfg( 3670): try to set false
I/GKI_LINUX( 3670): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3670): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 3670): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterState( 3670): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
D/HeadsetService( 3670): Received stop request...Stopping profile...
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/BluetoothHeadset( 1019): Proxy object disconnected
D/BluetoothHeadset( 1247): Proxy object disconnected
D/BluetoothHeadset( 1247): Proxy object disconnected
D/BluetoothHeadset( 1247): Proxy object disconnected
D/A2dpService( 3670): Received stop request...Stopping profile...
D/A2dpStateMachine( 3670): Exit Disconnected: -1
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
,D/BluetoothA2dp( 1019): Proxy object disconnected
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3670): Profile still running: com.android.bluetooth.hdp.HealthService
D/HidService( 3670): Received stop request...Stopping profile...
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
D/BluetoothAdapterState( 3670): Stopping profile services that were post enabled
W/BluetoothHeadsetServiceJni( 3670): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3670): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3670): Received stop request...Stopping profile...
I/jxcore-log( 3608): The client has disconnected!
I/jxcore-log( 3608): 
I/jxcore-log( 3608): Turning radios to false
I/jxcore-log( 3608): 
D/BluetoothAdapterService( 3670): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
D/PanService( 3670): Received stop request...Stopping profile...
D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1019): attempted to stop reverse tether with nothing tethered
D/BluetoothPan( 1019): BluetoothPAN Proxy object disconnected
D/BluetoothTethering( 1019): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@433172e8
D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
D/BluetoothInputDevice( 4639): Proxy object disconnected
D/HidProfile( 4639): Bluetooth service disconnected
I/GKI_LINUX( 3670): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3670): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 3670): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
I/jxcore-log( 3608): toggleBluetooth - 
I/jxcore-log( 3608): 
D/BtGatt.DebugUtils( 3670): handleDebugAction() action=null
D/BtGatt.GattService( 3670): Received stop request...Stopping profile...
D/BtGatt.GattService( 3670): stop()
D/BluetoothPan( 4639): BluetoothPAN Proxy object disconnected
D/PanProfile( 4639): Bluetooth service disconnected
D/WifiService( 1019): setWifiEnabled: false pid=3608, uid=10379
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3670): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothMapService( 3670): Received stop request...Stopping profile...
D/BluetoothMapService( 3670): stop()
D/BluetoothMapService( 3670): MAP Service closeService in
D/BluetoothMap( 4639): Proxy object disconnected
D/MapProfile( 4639): Bluetooth service disconnected
W/BluetoothHidServiceJni( 3670): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3670): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3670): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3670): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3670): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3670): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 3670): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3670): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3670): Cleaning up Bluetooth PAN callback object
I/jxcore-log( 3608): toggleWiFi
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
D/BluetoothAdapterService( 3670): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3670): cleanup()
D/BluetoothMapService( 3670): MAP Service closeService in
D/BluetoothAdapterState( 3670): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3670): Setting state to 10
I/BluetoothAdapterState( 3670): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3670): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
I/BluetoothAdapterState( 3670): Entering OffState
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=false
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
D/BluetoothPan( 1019): onBluetoothStateChange on: false
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=false
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
D/BluetoothMap( 4639): onBluetoothStateChange: up=false
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=false
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=false
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=false
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): ,
D/BluetoothPbap( 4639): onBluetoothStateChange: up=false
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
D/BluetoothPan( 4639): onBluetoothStateChange on: false
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
D/BluetoothInputDevice( 4639): onBluetoothStateChange: up=false
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceDown() to 9 receivers.
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@434dd2a0 mBinding = false
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): Sending unbind request.
D/BluetoothAdapterService( 3670): Cleaning up adapter native....
I/GKI_LINUX( 3670): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3670): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 3670): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/BluetoothServiceJni( 3670): cleanupNative: return from cleanup
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
D/BluetoothAdapterService( 3670): Done cleaning up adapter native....
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ,****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
D/BluetoothAdapterService(1107154512)( 3670): ****onDestroy()********
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): setWifiState: disabled
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 13 -> 10
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
D/BtGatt.GattService( 3670): cleanup()
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
W/bt-btif ( 3670): GATTC Module not enabled/already disabled
W/bt-btif ( 3670): GATTS Module not enabled/already disabled
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
D/BluetoothAdapter( 1081): 1108629272: getState() :  mService = null. Returning STATE_OFF
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): DBG, CoordinatorConnector too_late called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
W/XTWiFiOS( 1259): No entry in secure settings for enhanced location services: false
W/ContextImpl( 4639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/XTWiFiOS( 1259): Active network info is not available
W/Settings( 4433): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/XTCC-3.0.0.2(  575): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  575): [WwanPosMgr] handleConnectivtyStatusChange failed
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
E/XTCC-3.0.0.2(  575): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  575): [CSMgr] handleConnectivtyStatusChange failed
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): got too_late event, closing connection now.
I/jxcore-log( 3608): 
I/jxcore-log( 3608): CoordinatorConnector close called
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST TOOK:  ms ****
I/jxcore-log( 3608): 
I/jxcore-log( 3608): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 3608): 
I/chromium( 3608): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
D/DockEventReceiver( 4639): finishStartingService: stopping service
D/BluetoothAdapter( 4639): 1107200424: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1207): 1110303328: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1207): 1110303328: getState() :  mService = null. Returning STATE_OFF
V/BluetoothFtpReceiver( 3670): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3670): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 3670): Ftp Service onDestroy
V/BluetoothFtpService( 3670): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3670): Shutdown
D/AuthorizationBluetoothService( 1360): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1019): Killing 4433:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothAdapter( 4639): 1107200424: getState() :  mService = null. Returning STATE_OFF
W/Settings( 1207): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=4674 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1019): Killing 4515:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 4674): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/AndroidRuntime( 4692): 
D/AndroidRuntime( 4692): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4686): 
D/AndroidRuntime( 4686): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4692): CheckJNI is OFF
,D/AndroidRuntime( 4686): CheckJNI is OFF
,D/AndroidRuntime( 4695): 
D/AndroidRuntime( 4695): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4695): CheckJNI is OFF
,D/dalvikvm( 4692): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4686): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4686): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4692): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4686): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4692): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4692): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4686): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4692): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4686): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 4695): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 4695): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 4695): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4695): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 4695): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/NetlinkEvent(  271): Unexpected netlink message. type=0x11
W/Netd    (  271): No subsystem found in netlink event
D/TCMD    (  449): NL - Read 444 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 17
D/TCMD    (  449): Listening for incoming client connection request
D/dalvikvm( 4695): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
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
,D/dalvikvm( 4692): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/dalvikvm( 4686): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/TCMD    (  449): NL - Read 1000 bytes from update socket.
D/TCMD    (  449): NL - message type is RTM_NEWLINK
,D/TCMD    (  449): Listening for incoming client connection request
,D/NetlinkEvent(  271): Unexpected netlink message. type=0x11
W/Netd    (  271): No subsystem found in netlink event
D/TCMD    (  449): NL - Read 444 bytes from update socket.
D/TCMD    (  449): NL - ignore NL message, type = 17
D/TCMD    (  449): Listening for incoming client connection request
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
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,E/memtrack( 4695): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4695): failed to load memtrack module: -2
E/memtrack( 4692): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4692): failed to load memtrack module: -2
,E/memtrack( 4686): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4686): failed to load memtrack module: -2
,D/AndroidRuntime( 4695): Calling main entry com.android.commands.pm.Pm
,D/AndroidRuntime( 4692): Calling main entry com.android.commands.pm.Pm
,D/AndroidRuntime( 4686): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10379 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 3608:com.test.thalitest/u0a379 (adj 9): stop com.test.thalitest
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{445b2770 u0 com.test.thalitest/.MainActivity t3}
,I/WindowState( 1019): WIN DEATH: Window{42f06f30 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/PackageSettings( 1019): Skipping PackageSetting{422d2558 com.example.hello/10378} due to missing metadata
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10379 user=0: pkg removed
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1207): Ignoring removeGeofence because network location is disabled.
,D/VoicemailCleanupService( 4462): Cleaning up data for package: com.test.thalitest
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2154): GC_EXPLICIT freed 6095K, 44% free 9753K/17224K, paused 2ms+7ms, total 47ms
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
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
,D/dalvikvm( 1286): GC_EXPLICIT freed 2852K, 33% free 11631K/17224K, paused 2ms+53ms, total 135ms
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10379 #1
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/Launcher( 1286): Deferring update until onResume
,D/dalvikvm( 2198): GC_EXPLICIT freed 2745K, 43% free 9818K/17224K, paused 14ms+28ms, total 161ms
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/InternalIcingCorporaPro( 2198): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4728 uid=10059 gids={50059, 3003, 1028, 1015}
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447838188
,I/Launcher( 1286): Deferring update until onResume
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447838189
,I/InternalIcingCorporaPro( 2198): UpdateCorporaTask done [took 91 ms] updated apps [took 91 ms] 
,D/dalvikvm( 1019): GC_EXPLICIT freed 1976K, 64% free 18112K/49616K, paused 34ms+11ms, total 272ms
,D/AndroidRuntime( 4695): Shutting down VM
,D/dalvikvm( 4695): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10379 user=-1: uninstall pkg
,W/PackageSettings( 1019): Skipping PackageSetting{422d2558 com.example.hello/10378} due to missing metadata
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10379 user=0: pkg removed
,W/GeofencerStateMachine( 1207): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447838189
,I/Launcher( 1286): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/Launcher( 1286): Deferring update until onResume
,D/Checkin ( 2154): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196614
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10379 #1
,D/dalvikvm( 1019): GC_EXPLICIT freed 937K, 64% free 18051K/49616K, paused 4ms+10ms, total 104ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1019):   Scheme: "mms"
W/PackageManager( 1019): Package source /data/app/com.test.thalitest-1.apk does not exist.
,W/PackageManager( 1019): Couldn't delete native library directory /data/app-lib/com.test.thalitest-1
D/AndroidRuntime( 4692): Shutting down VM
D/dalvikvm( 4692): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10379 user=-1: uninstall pkg
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447838189
,F/PackageManager( 1019): Unable to write package manager settings, current changes will be lost at reboot
F/PackageManager( 1019): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager( 1019): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager( 1019): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager( 1019): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager( 1019): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager( 1019): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager( 1019): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager( 1019): 	at com.android.internal.util.FastXmlSerializer.escapeAndAppendString(FastXmlSerializer.java:145)
F/PackageManager( 1019): 	at com.android.internal.util.FastXmlSerializer.attribute(FastXmlSerializer.java:176)
F/PackageManager( 1019): 	at com.android.server.pm.PackageSignatures.writeXml(PackageSignatures.java:71)
F/PackageManager( 1019): 	at com.android.server.pm.Settings.writePackageLPr(Settings.java:1561)
F/PackageManager( 1019): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1328)
F/PackageManager( 1019): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:9492)
F/PackageManager( 1019): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:9637)
F/PackageManager( 1019): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:9746)
F/PackageManager( 1019): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:9353)
F/PackageManager( 1019): 	at com.android.server.pm.PackageManagerService.access$4100(PackageManagerService.java:178)
F/PackageManager( 1019): 	at com.android.server.pm.PackageManagerService$7.run(PackageManagerService.java:9287)
F/PackageManager( 1019): 	at android.os.Handler.handleCallback(Handler.java:733)
F/PackageManager( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
F/PackageManager( 1019): 	at android.os.Looper.loop(Looper.java:136)
F/PackageManager( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager( 1019): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager( 1019): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager( 1019): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager( 1019): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager( 1019): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager( 1019): 	... 20 more
,E/DropBoxManagerService( 1019): Can't write: system_server_wtf
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop27.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1019): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1019): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:470)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1469)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:9492)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:9637)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:9746)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:9353)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.access$4100(PackageManagerService.java:178)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService$7.run(PackageManagerService.java:9287)
E/DropBoxManagerService( 1019): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 1019): 	at android.os.Looper.loop(Looper.java:136)
E/DropBoxManagerService( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 23 more
F/PackageManager( 1019): Failed to clean up mangled file: /data/system/packages.xml
,E/DropBoxManagerService( 1019): Can't write: system_server_wtf
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop27.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1019): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1019): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1475)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.removePackageDataLI(PackageManagerService.java:9492)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.deleteInstalledPackageLI(PackageManagerService.java:9637)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.deletePackageLI(PackageManagerService.java:9746)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.deletePackageX(PackageManagerService.java:9353)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.access$4100(PackageManagerService.java:178)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService$7.run(PackageManagerService.java:9287)
E/DropBoxManagerService( 1019): 	at android.os.Handler.handleCallback(Handler.java:733)
E/DropBoxManagerService( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/DropBoxManagerService( 1019): 	at android.os.Looper.loop(Looper.java:136)
E/DropBoxManagerService( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 23 more
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10379 user=0: pkg removed
,E/SQLiteLog( 1019): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/GeofencerStateMachine( 1207): Ignoring removeGeofence because network location is disabled.
,I/Launcher( 1286): Deferring update until onResume
,E/SQLiteLog( 1286): (3850) statement aborts at 30: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,E/CheckinProvider( 1019): SQLiteDiskIOException:
E/CheckinProvider( 1019): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/CheckinProvider( 1019): 	at com.motorola.android.server.checkin.CheckinProvider.insertEvents(CheckinProvider.java:775)
E/CheckinProvider( 1019): 	at com.motorola.android.server.checkin.CheckinProvider.access$000(CheckinProvider.java:67)
E/CheckinProvider( 1019): 	at com.motorola.android.server.checkin.CheckinProvider$EventInsertThread.run(CheckinProvider.java:909)
,E/SQLiteLog( 2154): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
E/SQLiteDatabase( 2154): Error inserting state=an=null au=null avc=-1 avn=null name=com.test.thalitest st=2 timestamp=1447838189448 timezone=3600 name=PackageInfoTrigger
E/SQLiteDatabase( 2154): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2154): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2154): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2154): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2154): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2154): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2154): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2154): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2154): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2154): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2154): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2154): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2154): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2154): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2154): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2154): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,E/CheckinProvider( 1019): Exception:
E/CheckinProvider( 1019): java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
E/CheckinProvider( 1019): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
E/CheckinProvider( 1019): 	at com.motorola.android.server.checkin.CheckinProvider.insertEvents(CheckinProvider.java:798)
E/CheckinProvider( 1019): 	at com.motorola.android.server.checkin.CheckinProvider.access$000(CheckinProvider.java:67)
E/CheckinProvider( 1019): 	at com.motorola.android.server.checkin.CheckinProvider$EventInsertThread.run(CheckinProvider.java:909)
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447838189
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
F/PackageManager( 1019): Unable to backup user packages state file, current changes will be lost at reboot
,I/Launcher( 1286): Deferring update until onResume
,E/DropBoxManagerService( 1019): Can't write: system_server_wtf
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop69.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1019): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1019): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1019): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1019): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1019): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 19 more
W/ActiveOrDefaultContextProvider( 4728): Missing scope.enter somewhere. Returning default context
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,F/PackageManager( 1019): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 1019): Can't write: system_server_wtf
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop70.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10230)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10135)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10022)
E/DropBoxManagerService( 1019): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:337)
E/DropBoxManagerService( 1019): 	at android.util.Log$1.onTerribleFailure(Log.java:111)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:477)
E/DropBoxManagerService( 1019): 	at android.util.Log.wtf(Log.java:440)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1046)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:10124)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:10180)
E/DropBoxManagerService( 1019): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:974)
E/DropBoxManagerService( 1019): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:1538)
E/DropBoxManagerService( 1019): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 1019): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 1019): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1019): 	... 19 more
E/SQLiteDatabase( 4728): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4728),: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4728): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4728): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteDatabase( 4728): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteDatabase( 4728): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteDatabase( 4728): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteDatabase( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteDatabase( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteDatabase( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteDatabase( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteDatabase( 4728): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteDatabase( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteDatabase( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteDatabase( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4728): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteDatabase( 4728): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteDatabase( 4728): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4728): 	at amS.a(GellyInjector.java:117)
E/SQLiteDatabase( 4728): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4728): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:198)
E/SQLiteDatabase( 4728): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteDatabase( 4728): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteDatabase( 4728): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4728): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4728): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4728): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4728): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4728): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4728): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4728): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4728): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4728): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4728): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4728): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4728): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4728): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4728): 	at vR.b(ClientFlagDatabaseImpl.java:148)
E/SQLiteOpenHelper( 4728): 	at wd.a(ClientFlagsModule.java:31)
E/SQLiteOpenHelper( 4728): 	at wd.a(ClientFlagsModule.java:22)
E/SQLiteOpenHelper( 4728): 	at anh.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at iy.a(GellyInjectorStore.java:2144)
E/SQLiteOpenHelper( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at fM.a(GellyInjectorStore.java:87)
E/SQLiteOpenHelper( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at WB.a(GellyInjectorStore.java:73)
E/SQLiteOpenHelper( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at XX.a(GellyInjectorStore.java:123)
E/SQLiteOpenHelper( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4728): 	at apK.a(Scopes.java:65)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at fj.b(GellyInjectorStore.java:193)
E/SQLiteOpenHelper( 4728): 	at fj.a(GellyInjectorStore.java:306)
E/SQLiteOpenHelper( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at anh.a(GellyInjectorStoreBase.java:135)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at Jk.a(GellyInjectorStore.java:1093)
E/SQLiteOpenHelper( 4728): 	at amG.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper( 4728): 	at ann.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4728): 	at fj.a(GellyInjectorStore.java:91)
E/SQLiteOpenHelper( 4728): 	at fj.a(GellyInjectorStore.java:359)
E/SQLiteOpenHelper( 4728): 	at anj.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4728): 	at amS.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4728): 	at Ma.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4728): 	at com.google.android.apps.docs.DocsAp,plication.onCreate(DocsApplication.java:198)
E/SQLiteOpenHelper( 4728): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1030)
E/SQLiteOpenHelper( 4728): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4409)
E/SQLiteOpenHelper( 4728): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4728): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4728): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4728): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4728): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4728): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4728): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4728): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4728): 	at dalvik.system.NativeStart.main(Native Method)

```
