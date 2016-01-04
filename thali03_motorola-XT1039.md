#### Test 54970261c23922d_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1018): sending alarm Alarm{4314f228 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3517): 
D/AndroidRuntime( 3517): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3517): CheckJNI is OFF
D/dalvikvm( 3517): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3517): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3517): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3517): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3517): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3517): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3517): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3517): failed to load memtrack module: -2
D/AndroidRuntime( 3517): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3517
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3533 uid=10510 gids={50510, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3517): Shutting down VM
D/dalvikvm( 3517): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3533): Binding Chromium to main looper Looper (main, tid 1) {41f0ab78}
I/LibraryLoader( 3533): Expected native library version number "",actual native library version number ""
I/chromium( 3533): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3533): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothAdapter( 3533): 1106376104: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@439f2038:true
I/Adreno-EGL( 3533): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3533): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3533): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3533): Local Branch: 
I/Adreno-EGL( 3533): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3533): Local Patches: NONE
I/Adreno-EGL( 3533): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3533): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3533): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3533): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3533): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3533): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3533): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3533): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3533): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3533): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3533): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3533): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3533): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3533): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3533): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3533): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3533): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 3533): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3533): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3533): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3533): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3533): Enabling debug mode 0
,W/AwContents( 3533): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3533): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,402
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +378ms (total +402ms)
,D/JsMessageQueue( 3533): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3533): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f0f448
,D/dalvikvm( 3533): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f0f448
,D/jxcore_app_log( 3533): JniHelper::setJavaVM(0x41560fa8), pthread_self() = 1615237872
,D/JX-Cordova( 3533): jxcore cordova android initializing
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 3533): GC_CONCURRENT freed 2754K, 17% free 14435K/17224K, paused 1ms+2ms, total 48ms
,D/dalvikvm( 3533): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 137K, 17% free 14444K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 130K, 17% free 14459K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 16.244MB for 95956-byte allocation
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 178K, 17% free 14493K/17320K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 16.323MB for 143930-byte allocation
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 251K, 17% free 14541K/17464K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 16.438MB for 215890-byte allocation
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 366K, 18% free 14615K/17676K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 16.613MB for 323830-byte allocation
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 564K, 19% free 14735K/17996K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 16.885MB for 485740-byte allocation
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 860K, 20% free 14911K/18472K, paused 27ms, total 28ms
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 1279K, 18% free 15167K/18472K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 17.885MB for 1092904-byte allocation
,D/dalvikvm( 3533): GC_CONCURRENT freed 1768K, 21% free 15552K/19540K, paused 1ms+4ms, total 33ms
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 264K, 21% free 15496K/19540K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 18.729MB for 1639352-byte allocation
,D/dalvikvm( 3533): GC_CONCURRENT freed 1710K, 25% free 16064K/21144K, paused 3ms+4ms, total 34ms
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 1285K, 24% free 16121K/21144K, paused 29ms, total 31ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 20.121MB for 2459024-byte allocation
,D/dalvikvm( 3533): GC_CONCURRENT freed 214K, 22% free 18501K/23548K, paused 4ms+4ms, total 50ms
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 4382K, 28% free 17112K/23548K, paused 36ms, total 42ms
,I/dalvikvm-heap( 3533): Grow heap (frag case) to 22.260MB for 3688532-byte allocation
,D/dalvikvm( 3533): GC_CONCURRENT freed 370K, 25% free 20561K/27152K, paused 4ms+4ms, total 45ms
,D/dalvikvm( 3533): GC_FOR_ALLOC freed 3338K, 34% free 18076K/27152K, paused 29ms, total 29ms
,W/jxcore-log( 3533): Initializing JXcore engine
,W/jxcore-log( 3533): JXcore engine is ready
,D/dalvikvm( 3533): GC_CONCURRENT freed 379K, 24% free 20715K/27152K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 3533): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 3533): Starting JXcore engine
,W/jxcore-log( 3533): Platform android
W/jxcore-log( 3533): 
,W/jxcore-log( 3533): Process ARCH arm
W/jxcore-log( 3533): 
,V/AlarmManager( 1018): sending alarm Alarm{4314c698 type 3 android}
,I/jxcore-log( 3533): JXcore Cordova bridge is ready!
I/jxcore-log( 3533): 
,W/jxcore-log( 3533): JXcore engine is started
,I/chromium( 3533): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3533): Toggling radios to true
I/jxcore-log( 3533): 
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): enable():  mBluetooth =null mBinding = false
,W/Settings( 1252): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService( 1018): Message: 1
,D/BluetoothManagerService( 1018): MESSAGE_ENABLE: mBluetooth = null
,W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1018): New client listening to asynchronous messages
,W/XTWiFiOS( 1264): Active network info is not available
D/WifiService( 1018): setWifiEnabled: true pid=3533, uid=10510
E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager( 1018): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3579 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,W/Settings( 1252): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1252): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131145
,D/WifiStateMachine( 1018): setting operational mode to 1
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiStateMachine( 1018): processMsg: InitialState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131083
I/jxcore-log( 3533): Radios toggled
I/jxcore-log( 3533): 
D/WifiStateMachine( 1018): processMsg: InitialState
,W/Settings( 1252): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1264): Active network info is not available
,D/AdapterServiceConfig( 3579): Adding HeadsetService
D/AdapterServiceConfig( 3579): Adding A2dpService
D/AdapterServiceConfig( 3579): Adding HidService
D/AdapterServiceConfig( 3579): Adding HealthService
D/AdapterServiceConfig( 3579): Adding PanService
D/AdapterServiceConfig( 3579): Adding GattService
,D/AdapterServiceConfig( 3579): Adding BluetoothMapService
,D/BluetoothAdapterService( 3579): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1018): Message: 20
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@438dc7f0:true
,D/BluetoothAdapterState( 3579): make
,I/bluedroid( 3579): init
,I/BluetoothAdapterState( 3579): Entering OffState
,I/bte_conf( 3579): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3579): get_profile_interface socket
,D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1018): Message: 40
,D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/GKI_LINUX( 3579): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:2 len:6
,I/bluedroid( 3579): config_hci_snoop_log
,D/BluetoothAdapterProperties( 3579): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothManagerService( 1018): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
,D/BluetoothAdapterProperties( 3579): Name is: XT1039
,D/BluetoothAdapterState( 3579): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3579): Setting state to 11
I/BluetoothAdapterState( 3579): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3579): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3579): make
,I/BluetoothBondStateMachine( 3579): StableState(): Entering Off State
,I/ActivityManager( 1018): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3612 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/BluetoothHeadset( 1018): Proxy object connected
,D/BluetoothHeadset( 1239): Proxy object connected
D/BluetoothHeadset( 1239): Proxy object connected
,D/BluetoothHeadset( 1239): Proxy object connected
,I/BluetoothAdapterState( 3579): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetService( 3579): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3579): classInitNative: succeeds
D/HeadsetStateMachine( 3579): Version 1.6
,D/HeadsetStateMachine( 3579): make
,I/bluedroid( 3579): get_profile_interface handsfree
,D/BluetoothA2dp( 1018): Proxy object connected
,D/A2dpService( 3579): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3579): classInitNative: succeeds
V/Avrcp   ( 3579): make
,I/bluedroid( 3579): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 3579): classInitNative: succeeds
,D/A2dpStateMachine( 3579): make
I/bluedroid( 3579): get_profile_interface a2dp
,I/GKI_LINUX( 3579): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3579): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3579): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3579): classInitNative: succeeds
D/HidService( 3579): Received start request. Starting profile...
,I/bluedroid( 3579): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3579): classInitNative: succeeds
,D/HealthService( 3579): Received start request. Starting profile...
,I/bluedroid( 3579): get_profile_interface health
,I/BluetoothPanServiceJni( 3579): classInitNative(L105): succeeds
,D/BluetoothPan( 1018): BluetoothPAN Proxy object connected
D/PanService( 3579): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3579): initializeNative(L110): pan
,I/bluedroid( 3579): get_profile_interface pan
D/BluetoothTethering( 1018): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1018): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@4388fd58
,I/BtGatt.JNI( 3579): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3579): handleDebugAction() action=null
D/BtGatt.GattService( 3579): Received start request. Starting profile...
D/BtGatt.GattService( 3579): start()
,I/bluedroid( 3579): get_profile_interface gatt
,D/BluetoothMapService( 3579): Received start request. Starting profile...
,D/BluetoothMapService( 3579): start()
,D/HeadsetPhoneState( 3579): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3579): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3579): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3579): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3579): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3579): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3579): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/HeadsetPhoneState( 3579): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 3579): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3579): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3579): enable
,I/bt_hci_bdroid( 3579): init
I/bt_vendor( 3579): bt-vendor : init
I/bt_hci_bdroid( 3579): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3579): userial_init
I/bt_hwcfg( 3579): Starting hciattach daemon
I/bt_hwcfg( 3579): try to set false
I/bt_hci_bdroid( 3579): bt_hc_worker_thread started
I/bt_hwcfg( 3579): Starting hciattach daemon
,I/bt_hwcfg( 3579): try to set true
,I/qcom-bluetooth( 3642): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager( 1018): Killing 3285:com.android.calendar/u0a7 (adj 15): empty #9
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
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/TCMD    (  446): NL - Read 1004 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1018): InitialState.processMessage what=4
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,I/MDMCTBK (  273): NetlinkHandler, subsys is net and action is add
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
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
,E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  446): NL - Read 1004 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,I/qcom-bluetooth( 3650): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/QsoftapCmd(  270): Got softap fwreload command we are passing on
,D/SoftapController(  270): Softap fwReload - Ok
,I/qcom-bluetooth( 3652): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/WifiService( 1018): New client listening to asynchronous messages
,D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring down wlan0
,I/qcom-bluetooth( 3655): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3656): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 3657): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,E/WifiHW  ( 1018): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1018): ctrl_interface != /data/misc/wifi/sockets
,E/Diag_Lib( 3659): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3659): Setting internal use port to rmnet0
E/Diag_Lib( 3659):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
E/Diag_Lib( 3659): Failed on DIAG init
E/Diag_Lib( 3659): linux_qmi_qmux_if_client_get_proc_name: pid=3659, proc_name=hci_qcomm_init
E/Diag_Lib( 3659): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3659): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3659): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3659): qmi_client [3659]: successfully connected to server, attempt=1
E/Diag_Lib( 3659): linux_qmi_qmux_if_client_get_client_id [3659]: qmux_client_id=13
E/Diag_Lib( 3659): qmi_client [3659] 13: qmux_client ID is initialized
E/Diag_Lib( 3659): qmi_client [3659] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3659): qmi_client [3659] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3659): qmi_client [3659] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3659): Sending signal ...... to read cmd data 
E/Diag_Lib( 3659): qmi error code.........:0
E/Diag_Lib( 3659): qmi sys error code.........:0
E/Diag_Lib( 3659): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3659): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3659): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3659): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3659): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3659): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3659): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3659): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3659): qmi_init:  Created client handle b8864788
,E/Diag_Lib( 3659): qmi_client [3659] 13: sending 880 bytes on fd = 8
,V/BluetoothFtpReceiver( 3579): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
E/Diag_Lib( 3659): qmi_client [3659] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3659): Sending signal ...... to read cmd data 
E/Diag_Lib( 3659): qmi error code.........:0
E/Diag_Lib( 3659): qmi sys error code.........:0
E/Diag_Lib( 3659): Setting the api flag to : 1
E/Diag_Lib( 3659): qmi_client [3659] 13: sending 54 bytes on fd = 8
,D/AuthorizationBluetoothService( 2013): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 3661): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3661): rfkill: Cannot open RFKILL control device
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,D/WifiStateMachine( 1018): setWifiState: enabling
D/WifiStateMachine( 1018): Supplicant start successful
,D/WifiMonitor( 1018): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1264): Active network info is not available
,E/Diag_Lib( 3661): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3661): Setting internal use port to rmnet0
I/rmt_storage(  428): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7a351d0
I/rmt_storage(  428): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  428): wakelock acquired: 1, error no: 42
I/rmt_storage(  428): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1214033352)
E/Diag_Lib( 3659): qmi_client [3659] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3659):  API Flag .............. 1 
,E/Diag_Lib( 3659):  Message ID ............... 92 
,E/wpa_supplicant( 3661): baseband property is set to [msm]
,E/wpa_supplicant( 3661):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3661): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3661): card_info[i].card_state: 0x2
E/wpa_supplicant( 3661): card_info[i].error_code: 0x3
E/wpa_supplicant( 3661): SIM/USIM not ready
E/wpa_supplicant( 3661): Error while reading SIM card status
,E/wpa_supplicant( 3661): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3661): card_info[i].card_state: 0x2
E/wpa_supplicant( 3661): card_info[i].error_code: 0x3
E/wpa_supplicant( 3661): SIM/USIM not ready
,I/wpa_supplicant( 3661): eap_proxy: Card not ready
,E/Diag_Lib( 3659): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3659): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3659): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3659): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3659): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3659): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3659): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3659): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3659): qmi_client [3659] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3659): qmi_client [3659] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3659): Sending signal ...... to read cmd data 
E/Diag_Lib( 3659): qmi error code.........:0
E/Diag_Lib( 3659): qmi sys error code.........:0
E/Diag_Lib( 3659): qmi_release: Released client handle ff
E/Diag_Lib( 3659): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3659): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3659): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3659): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3659): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3659): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3659): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3659): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3659): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3659): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3659): qmi_client [3659] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3659): qmi_client [3659] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3659): Sending signal ...... to read cmd data 
E/Diag_Lib( 3659): qmi error code.........:0
E/Diag_Lib( 3659): qmi sys error code.........:0
E/Diag_Lib( 3659): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3659] 13
E/Diag_Lib( 3659): qmi_client [3659] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3659): qmi_client [3659] 13: failed to locate client data
E/Diag_Lib( 3659): qmi_client [3659] 13: calling release of fd=8
,E/Diag_Lib( 3659): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,I/rmt_storage(  428): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  428): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  428): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1214033352) wakelock released: 1, error no: 0
I/rmt_storage(  428): 
,I/rmt_storage(  428): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7a351d0
,I/wpa_supplicant( 3661): Long line in configuration file truncated
,I/wpa_supplicant( 3661): rfkill: Cannot open RFKILL control device
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,I/qcom-bluetooth( 3665): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3666): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 3579): bluetooth satus is on
,D/bt_userial_mct( 3579): userial_open(port:0)
I/bt_userial_vendor( 3579): Done intiailizing UART
I/GKI_LINUX( 3579): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3579): btu_task pending for preload complete event
I/bt_userial_vendor( 3579): Done intiailizing UART
I/bt_userial_mct( 3579): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3579): Bluetooth Firmware and smd is initialized
I/bt-btu  ( 3579): btu_task received preload complete event
,D/bt_userial_mct( 3579): Entering userial_read_thread()
I/        ( 3579): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3579): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3579): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3579): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3579): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3579): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3579): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3579): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3579): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3579): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3579): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3579): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3579): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3579): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3579): BTE_InitTraceLevels -- TRC_BTIF
,E/wpa_supplicant( 3661): COUNTRY Code Recived
,E/wpa_supplicant( 3661): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3661): baseband property is set to [msm]
,E/wpa_supplicant( 3661):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3661): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3661): card_info[i].card_state: 0x2
E/wpa_supplicant( 3661): card_info[i].error_code: 0x3
E/wpa_supplicant( 3661): SIM/USIM not ready
,E/wpa_supplicant( 3661): Error while reading SIM card status
,E/wpa_supplicant( 3661): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 3661): card_info[i].card_state: 0x2
E/wpa_supplicant( 3661): card_info[i].error_code: 0x3
E/wpa_supplicant( 3661): SIM/USIM not ready
,I/wpa_supplicant( 3661): eap_proxy: Card not ready
,D/WifiStateMachine( 1018): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: InitialState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
,D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
E/bt-btm  ( 3579): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f0a2049 
E/bt-btm  ( 3579): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f0a2049 
,D/WifiStateMachine( 1018): deferMessage: msg=131144
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
,D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): deferMessage: msg=131085
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131149
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): setSuspendOptimizations: 2 true
D/WifiStateMachine( 1018): mSuspendOptNeedsDisabled 0
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131146
,D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147457
D/WifiStateMachine( 1018): processMsg: SupplicantStartingState
D/WifiStateMachine( 1018): Supplicant connection established
,D/WifiStateMachine( 1018): setWifiState: enabled
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1264): Active network info is not available
,E/bt-btif ( 3579): Calling BTA_HhEnable
E/bt-btif ( 3579): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3579): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothAdapterProperties( 3579): Name is: XT1039
,I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService( 1018): Bluetooth Adapter name changed to XT1039
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/BluetoothManagerService( 1018): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3579): Scan Mode:21
I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3579): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:8 len:0
I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:3 len:48
,I/bte_conf( 3579): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3579): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3579): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 3579): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3579): hci lib postload completed
,D/BluetoothAdapterState( 3579): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3579): ScanMode =  21
D/BluetoothAdapterProperties( 3579): State =  11
D/BluetoothAdapterProperties( 3579): Setting state to 12
,I/BluetoothAdapterState( 3579): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 3579): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1018): Message: 60
D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
D/BluetoothPan( 1018): onBluetoothStateChange on: true
,D/BluetoothHeadset( 1018): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3579): Entering On State
,D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1018): onBluetoothStateChange: up=true
,D/BluetoothManagerService( 1018): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothAdapterService(1106363808)( 3579): Get Bonded Devices being called
D/BluetoothManagerService( 1018): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterService(1106363808)( 3579): Get Bonded Devices being called
D/BluetoothPanServiceJni( 3579): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3579): Discoverable Timeout:120
D/BluetoothManagerService( 1018): Message: 40
,D/BluetoothManagerService( 1018): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/WifiConfigStore( 1018): Loading config and enabling all networks
,D/BluetoothMapService( 3579): onReceive
D/BluetoothMapService( 3579): STATE_ON
,D/BluetoothMapService( 3579): Map Service startRfcommSocketListener
,D/BluetoothMapService( 3579): Map Service initSocket
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/BluetoothAdapterService(1106363808)( 3579): Get Bonded Devices being called
,W/BluetoothAdapter( 3579): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3579): SOCK FLAG = 1 ***********************
,I/BluetoothAdapterProperties( 3579): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3579): Scan Mode:21
,D/BluetoothMapService( 3579): Accepting socket connection...
,E/WifiConfigStore( 1018): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/qcom-bt-wlan-coex( 3680): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,E/wpa_supplicant( 3661): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1018): transitionTo: destState=DriverStartedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1018): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1018): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1018): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1018): setDetailed state, old =IDLE and new state=DISCONNECTED
,W/ContextImpl( 3612): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
E/wpa_supplicant( 3661): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3661): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/WifiStateMachine( 1018): Attempting to reconnect to wifi network ..
D/WifiStateMachine( 1018): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1018): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1018): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectModeState
,D/WifiStateMachine( 1018): invokeEnterMethods: DisconnectedState
D/WifiP2pService( 1018): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothPbapService( 3579): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3579): Handler(): got msg=1
D/BluetoothManagerService( 1018): Message: 20
,D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c26cb0:true
D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring up p2p0
D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131144
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiMonitor( 1018): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1018): P2pEnablingState
D/WifiP2pService( 1018): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2p socket connection successful
W/BluetoothAdapter( 3579): getBluetoothService() called with no BluetoothManagerCallback
D/WifiStateMachine( 1018): handleMessage: E msg.what=131085
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiP2pService( 1018): P2pEnabledState
E/BluetoothServiceJni( 3579): SOCK FLAG = 1 ***********************
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiP2pService( 1018): sending p2p connection changed broadcast
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131152
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): set country code PL
D/LocalBluetoothProfileManager( 3612): Adding local A2DP profile
D/BluetoothManagerService( 1018): Message: 30
E/wpa_supplicant( 3661): COUNTRY Code Recived
E/wpa_supplicant( 3661): COUNTRY Code Recived
,D/WifiP2pService( 1018): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131162
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): set frequency band 2
W/ContextImpl( 3612): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
,D/WifiP2pService( 1018): MCC mode enabled 0
W/wpa_supplicant( 3661): wlan0: Failed to initiate AP scan
D/LocalBluetoothProfileManager( 3612): Adding local HEADSET profile
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
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
,D/BluetoothManagerService( 1018): Message: 30
D/WifiP2pService( 1018): mP2pAutoConnectSupport = 0
W/ContextImpl( 3612): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/WifiP2pService( 1018): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1018): InactiveState
D/WifiP2pService( 1018): InactiveState{ when=-16ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-16ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): InactiveState{ when=-18ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-18ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1018): Message: 30
E/wpa_supplicant( 3661): COUNTRY Code Recived
,E/wpa_supplicant( 3661): COUNTRY Code Recived
D/WifiP2pService( 1018): InactiveState{ when=-18ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=-18ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 3612): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,W/ContextImpl( 3612): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3612): Adding local MAP profile
,D/BluetoothMap( 3612): Create BluetoothMap proxy object
W/ContextImpl( 3612): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,W/ContextImpl( 3612): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3612): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3612): finishStartingService: stopping service
,D/BluetoothAdapterService(1106363808)( 3579): Get Bonded Devices being called
,D/BluetoothA2dp( 3612): Proxy object connected
,D/A2dpProfile( 3612): Bluetooth service connected
,D/BluetoothHeadset( 3612): Proxy object connected
,D/HeadsetProfile( 3612): Bluetooth service connected
,D/BluetoothInputDevice( 3612): Proxy object connected
,D/HidProfile( 3612): Bluetooth service connected
,D/BluetoothPan( 3612): BluetoothPAN Proxy object connected
,D/PanProfile( 3612): Bluetooth service connected
,D/BluetoothMap( 3612): Proxy object connected
D/MapProfile( 3612): Bluetooth service connected
,D/BluetoothMap( 3612): getConnectedDevices()
,D/BluetoothPbap( 3612): Proxy object connected
,D/PbapServerProfile( 3612): Bluetooth service connected
,V/BluetoothFtpReceiver( 3579): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3579): BluetoothFtpReceiver Start Service
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3579): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3579): SOCK FLAG = 0 ***********************
V/BluetoothFtpService( 3579): Ftp Service onCreate
I/BluetoothFtpService( 3579): FFFFFtp Service onCreate
V/BluetoothFtpService( 3579): Starting FTP service
,I/BtOppRfcommListener( 3579): Accept thread started.
,V/BluetoothFtpService( 3579): Ftp Service onStartCommand
V/BluetoothFtpService( 3579): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3579): Handler(): got msg=1
V/BluetoothFtpService( 3579): Ftp Service startRfcommSocketListener
V/BluetoothFtpService( 3579): Ftp Service initSocket
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3579): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3579): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3579): Succeed to create listening socket on channel 20
V/BluetoothFtpService:RfcommSocketAcceptThread( 3579): Run Accept thread
D/AuthorizationBluetoothService( 2013): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2013): Proximity feature is not enabled.
,D/dalvikvm( 1018): GC_EXPLICIT freed 23050K, 65% free 17907K/50512K, paused 4ms+11ms, total 183ms
,D/BluetoothManagerService( 1018): Message: 30
D/BluetoothManagerService( 1018): Message: 30
,D/BluetoothManagerService( 1018): Message: 30
,D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,I/MDMCTBK (  273): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  273): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): wifi_connect_to_supplicant, current pid is = 273
D/MDMCTBK (  273): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  273): wifi_close_sockets: Exit
E/MDMCTBK (  273): Attach monitor thread
,I/MDMCTBK (  273): createWifiMonitorThread: Started the wifi monitor thread -1216457616
,D/MDMCTBK (  273): wifi_wait_on_socket: Enter monitor thread
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,W/wpa_supplicant( 3661): wlan0: Failed to initiate AP scan
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <4>Failed to initiate AP scan
,D/MDMCTBK (  273): Event received = Failed to initiate AP scan
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledStateupdate channel list
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2149): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/wpa_supplicant( 3661): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c0:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 0 c0:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c2:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 1 c2:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 2 38:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 3 64:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 06:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 4 06:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 64:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 64:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 a0:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 a0:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 e8:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 e8:
D/MDMCTBK (  273): reply_len: 42 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 00:
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 00:
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 3660): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3660): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/TCMD    (  446): NL - Read 56 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  273): Event received = Trying to associate with
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,E/wpa_supplicant( 3661): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  446): NL - Read 312 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 192 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 68 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
I/wpa_supplicant( 3661): WEXT: Custom wireless event: 'BEACONIEs='
,I/wpa_supplicant( 3661): WEXT: Custom wireless event: 'BEACONIEs='
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3661): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  273): Event received = Associated with c0:ff:d4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  446): NL - Read 80 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 80 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
D/TCMD    (  446): Listening for incoming client connection request
D/TCMD    (  446): NL - Read 68 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3661): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3661): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  273): Event received = WPA: Key negotiation com
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  273): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  273):  STA Connected !!
D/TCMD    (  446): NL - Read 1000 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
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
I/MDMCTBK (  273): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1216461720
I/MDMCTBK (  273): return from set_get_from_wpa_supplicant
I/MDMCTBK (  273): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  273): set_property_value, Enter
I/MDMCTBK (  273): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  273): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  273): set_property_value, Exit
E/MDMCTBK (  273): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
D/MDMCTBK (  273): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  273): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  273): , reply_len: 3, ret: 0
E/MDMCTBK (  273): MdmCutbackHndler, resp=OK
E/MDMCTBK (  273): 
,D/MDMCTBK (  273): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=147459
,D/WifiStateMachine( 1018): processMsg: DisconnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): Network connection established
,D/WifiStateMachine( 1018): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/Tethering( 1018): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
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
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147462
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-58ms what=147462 obj=android.net.wifi.StateChangeResult@421298e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=131101
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
,D/WifiStateMachine( 1018): ObtainingIpState{ when=-45ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@424fb748 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-7ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1018): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427932f0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@427932f0 target=com.android.internal.util.StateMachine$SmHandler }
,D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 1
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 1
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
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 a0
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 6 a0
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 10
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 7 10
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 e8
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 8 e8
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 00
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-ADDED 9 00
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  273): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
,D/MDMCTBK (  273): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  446): NL - Read 56 bytes from update socket.
D/TCMD    (  446): NL - message type is RTM_NEWLINK
,D/TCMD    (  446): Listening for incoming client connection request
,D/WifiStateMachine( 1018): handleMessage: E msg.what=147461
D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiP2pService( 1018): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): InactiveState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@41f5c2e0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=-2ms what=147462 obj=android.net.wifi.StateChangeResult@41f5c2e0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): DefaultState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@41f5c2e0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1018): handleMessage: X
,D/TCMD    (  446): NL - Read 60 bytes from update socket.
D/TCMD    (  446): NL - ignore NL message, type = 20
D/TCMD    (  446): Listening for incoming client connection request
,D/WifiStateMachine( 1018): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
,D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/WifiStateMachine( 1018): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1018): processMsg: ObtainingIpState
D/WifiStateMachine( 1018): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,D/WifiStateMachine( 1018): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1018): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1018): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1018): DHCP successful
D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine( 1018): Calling ARP set with IP = 192.168.1.127
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
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=151572
,D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
D/WifiStateMachine( 1018): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine( 1018): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=135190
D/WifiStateMachine( 1018): processMsg: VerifyingLinkState
,D/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 1018): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1018): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState enter
,D/WifiStateMachine( 1018): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1018): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1018): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1018): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,V/ConnectivityService( 1018): WiFi NOT Tethered!
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff0668
,D/WifiStateMachine( 1018): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1018): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1018): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1018): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1018): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1018): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1018): invokeEnterMethods: ConnectedState
D/WifiStateMachine( 1018): handleMessage: X
D/WifiStateMachine( 1018): handleMessage: E msg.what=131092
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): handleMessage: X
,D/Checkin ( 1018): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1283): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1283): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1283): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1018): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1018): WiFi NOT Tethered!
E/ConnectivityService( 1018): Unexpected mtu value: android.net.wifi.WifiStateTracker@41ff0668
D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1283): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1283): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1283): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,D/CaptivePortalTracker( 1018): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        ( 1018): Setting time of day to sec=1451923567
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,W/        ( 1018): Unable to set rtc to 1451923567: Invalid argument
D/PollingManager( 1541): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/ActivityManager( 1018): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3765 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/PollingManager( 1541): now: 231364 ,futureTime: 86439428
,D/PollingManager( 1541): Polling alarm set to expire at: 86439428 Current Time: 231364
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,E/ActivityThread( 1541): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1541): registerApp(): CCE
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
I/CCE     ( 1541): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1264): No entry in secure settings for enhanced location services: false
D/CCE     ( 1541): Registering with Alarm Manager to restart CCE
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/MMApiWebService( 1541): Received data connectivity intent from PollingManager .. retry the waiting requests: 3
D/CCE     ( 1541): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1541): isRequestAllowed(): already have outstanding request ... ignoring request
D/PollingManager( 1541): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/OtaApp  ( 1541): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1541): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
D/PollingManager( 1541): now: 231426 ,futureTime: 86439428
,D/PollingManager( 1541): Polling alarm set to expire at: 86439428 Current Time: 231426
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1541): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,E/ActivityThread( 1541): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1541): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1541): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1541): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1541): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1541): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1541): GC_CONCURRENT freed 2479K, 38% free 10715K/17224K, paused 3ms+3ms, total 40ms
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/MMApiWebService( 1541): generating token using payload instead of using session token
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1202): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1202): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1202): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1202): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1202): Using platform SSLCertificateSocketFactory
,I/ActivityManager( 1018): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3799 uid=10056 gids={50056, 3003, 1028, 1015}
I/MMApiWSBase( 1541): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWSBase( 1541): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/ChimeraCfgMgr( 1343): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1343): Module APK com.google.android.play.games already loaded
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,I/GamesSyncServiceMain( 1343): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1343): Failed to execute periodic sync, missing client context - aborting
,D/dalvikvm( 3765): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f151e0, skipping init
I/openssl ( 3765): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3765): Crypto mode 0 already enabled
,I/PhenotypeConfigurator( 1202): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/DownloadManager( 3765): Download 317 starting
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3826 uid=10030 gids={50030, 3003, 1028, 1015}
W/ActivityThread( 3765): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/dalvikvm( 1343): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1343): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1343): VFY: replacing opcode 0x6e at 0x003d
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/GpsLocationProvider( 1018): NTP server returned: 1451923564834 (Mon Jan 04 17:06:04 CET 2016) reference: 228418 certainty: 10 system time offset: -3425
,E/ActivityThread( 1343): Failed to find provider info for com.android.contacts.metadata
E/LocSvc_ApiV02( 1018): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,V/MmsConfig( 3826): mnc/mcc: 
,V/MmsConfig( 3826): tag: bool value: enabledMMS - true
V/MmsConfig( 3826): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3826): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3826): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3826): tag: int value: defaultSMSMessagesPerThread - 500
D/DelayedSyncController( 3799): Delaying sync.
V/MmsConfig( 3826): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3826): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3826): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3826): tag: int value: recipientLimit - 20
V/MmsConfig( 3826): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3826): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3826): tag: bool value: enableSlideDuration - true
,V/MmsConfig( 3826): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3826): tag: int value: maxSubjectLength - 80
V/MmsConfig( 3826): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3826): tag: bool value: smsForce7BitEncoding - false
,V/MmsConfig( 3826): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3826): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 231889, reason: UserStart
,I/ActivityManager( 1018): Killing 3378:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/dalvikvm( 1202): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
I/ActivityManager( 1018): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3853 uid=10041 gids={50041, 3003}
I/ActivityManager( 1018): Killing 3043:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/dalvikvm( 1202): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1202): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 2013): GC_EXPLICIT freed 1825K, 41% free 10283K/17224K, paused 8ms+18ms, total 113ms
,D/MobileConnectivityChangeReceiver( 3853): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3853): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3853): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3853): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3867 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3405:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1343): Checkin interval check for package: unspecified last checkin: 1451341410311 min interval config: 0 actual interval: 582158133
,D/dalvikvm( 1239): GC_EXPLICIT freed 1455K, 45% free 9515K/17224K, paused 2ms+27ms, total 144ms
,I/CheckinService( 1343): Checking schedule, now: 1451923568466 next: 1451341440246
,I/CheckinService( 1343): active receiver: enabled
,E/Auth.Api.Credentials( 1343): [CredentialSyncAdapter] Unknown sync event.
,I/CheckinService( 1343): Preparing to send checkin request
,I/EventLogService( 1343): Accumulating logs since 1451923231542
,I/dalvikvm( 1018): Jit: resizing JitTable from 8192 to 16384
,V/WebViewChromiumFactoryProvider( 3867): Binding Chromium to main looper Looper (main, tid 1) {41f12120}
,I/LibraryLoader( 3867): Expected native library version number "",actual native library version number ""
,I/chromium( 3867): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3867): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3867): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3867): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3867): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3867): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3867): Local Branch: 
I/Adreno-EGL( 3867): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3867): Local Patches: NONE
I/Adreno-EGL( 3867): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1343): Checkin reason type: 8 attempt count: 1
,W/chromium( 3867): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,D/WifiService( 1018): New client listening to asynchronous messages
,E/ActivityThread( 1343): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1018): GC_EXPLICIT freed 1873K, 65% free 17890K/50512K, paused 6ms+10ms, total 109ms
,W/GAV2    ( 3867): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/DelayedSyncController( 3799): Delaying sync.
,E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3867): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NSApplication( 3867): Starting up...
,I/DownloadManager( 3765): Ignoring Content-Length since Transfer-Encoding is also defined
,W/dalvikvm( 2013): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/ImageResourceManager( 3076): ImageResourceManager: uninitalized
E/dalvikvm( 2013): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 2013): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 2013): VFY: replacing opcode 0x1f at 0x0011
,I/iu.Environment( 3076): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/dalvikvm( 2013): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2013): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2013): VFY: replacing opcode 0x6e at 0x003d
,I/iu.SyncManager( 3076): SYNC; picasa accounts
I/ActivityManager( 1018): Killing 3059:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3076): num queued entries: 0
,I/iu.UploadsManager( 3076): num updated entries: 0
,I/iu.SyncManager( 3076): NEXT; no task
,I/iu.SyncManager( 1343): SYNC; picasa accounts
,D/NetworkLogImpl( 1343): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1343): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/DEBUG   ( 1541): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1541): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1541): ServiceHandler.handleMessage: mWaitCount=1
,I/iu.UploadsManager( 1343): num queued entries: 0
,D/EmailService.MarketingOptInSetter( 1541): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/iu.UploadsManager( 1343): num updated entries: 0
,D/Checkin ( 3765): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/iu.SyncManager( 1343): NEXT; no task
,D/MobileConnectivityChangeReceiver( 3853): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3853): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3076): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/DownloadManager( 3765): Download 317 finished with status SUCCESS
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3925 uid=10007 gids={50007, 3003}
,I/ActivityManager( 1018): Killing 3432:com.google.android.apps.docs/u0a59 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/WifiStateMachine( 1018): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1018): handleMessage: E msg.what=131215
D/WifiStateMachine( 1018): processMsg: ConnectedState
D/WifiStateMachine( 1018): processMsg: L2ConnectedState
D/WifiStateMachine( 1018): processMsg: ConnectModeState
D/WifiStateMachine( 1018): processMsg: DriverStartedState
D/WifiStateMachine( 1018): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1018): processMsg: DefaultState
,D/WifiStateMachine( 1018): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1018): handleMessage: X
,D/ConnectivityService( 1018): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1018):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService( 1018): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1018): requiresClat: netType=1, hasIPv4Address=true
,I/MMApiWSBase( 1541): doRequest(): error in response: 403
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/ExtensionsFactory( 3925): No custom extensions.
,I/MMApiWSBase( 1541): doRequest(): error in response: {"error":"INVALID_SESSION","error_text":"Please provide a valid authtoken"}
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 1541): doRequest(): v1/ns/list/messages resp length: 75
,I/MMApiWebService( 1541): _inspectMMApiResponse(): found an error from a web service response: ForbiddenError msg: INVALID_SESSION req: 
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1541): _inspectMMApiResponse(): received invalid session error from the server.. need to re-login
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3942 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 3111:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/MMApiWebService( 1541): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3954 uid=10008 gids={50008, 3003, 1028, 1015}
D/MMApiProvisionService( 1541): Got request to obtain new Session .. doing so now
D/MMApiProvisionService( 1541): isRequestAllowed(): already have outstanding request ... ignoring request
D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,I/ActivityManager( 1018): Killing 3612:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
,D/WifiService( 1018): Client connection lost with reason: 4
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,V/AlarmClock( 3942): AlarmInitReceiver android.intent.action.TIME_SET
,I/MMApiWSBase( 1541): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/check.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,I/GCM     ( 2013): GCM config loaded
,I/CalendarProvider2( 3954): Created com.android.providers.calendar.CalendarAlarmManager@41f2dda8(com.android.providers.calendar.CalendarProvider2@41f25960)
,D/MMApiProvisionService( 1541): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"172742","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1541): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1541): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1541): MMApiProvisionService.handleResponse (update_device) : true (None)
,I/AlarmClock( 3942): Displaying next alarm time: ''
,D/MMApiProvisionService( 1541): handleResponse(): Session Expiration alarm set to expire at: Wed Jan 06 17:05:11 CET 2016
,V/AlarmClock( 3942): AlarmInitReceiver finished
,D/MMApiProvisionService( 1541): _setMMApiCredInfo: storing credential info 
I/ActivityManager( 1018): Killing 3765:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3975 uid=10098 gids={50098}
,E/MMApiProvisionService( 1541): handleResponse(): no settings sent by the server:
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1541): MMApiWebService told us to retry waiting request since device is successfully provisioned: 1
,D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1541): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 3975): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41f0ee58, skipping init
D/TimeService( 3975): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1451923569449
D/        ( 3975): TimeServiceNative: User Time to be set is 1451923569449
D/QC-time-services( 3975): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3975): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3975): Lib:time_genoff_operation: pargs->ts_val = 1451923569449
,D/QC-time-services(  417): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3975): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  417): Daemon:Received base = 2, unit = 1, operation = 0,value = 1451923569449
D/QC-time-services(  417): Daemon:genoff_opr: Base = 2, val = 1451923569449, operation = 0
D/QC-time-services(  417): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/4/116 16:0:10
D/QC-time-services(  417): Daemon:Value read from RTC seconds = 1451923210000
,D/QC-time-services(  417): Daemon:new time 1451923569449 
D/QC-time-services(  417): Daemon: delta 359449 genoff 359449 
D/QC-time-services(  417): Daemon:genoff_persistent_update: Writing genoff = 359449 to memory
D/QC-time-services(  417): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  417): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  417): Updating the TOD offset
D/QC-time-services(  417): Daemon:genoff_persistent_update: Writing genoff = 359449 to memory
D/QC-time-services(  417): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  417): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  417): Daemon:Update to modem bit set
E/QC-time-services( 3975): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  417): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  417): Daemon: Base = 2, Value being sent to MODEM = 18446743757745111065
E/QC-time-services(  417): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  417): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1343): Checkin interval check for package: unspecified last checkin: 1451341410311 min interval config: 0 actual interval: 582159155
,D/DEBUG   ( 1541): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1541): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1541): ServiceHandler.handleMessage: mWaitCount=1
,D/EmailService.MarketingOptInSetter( 1541): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1541): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1541): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1541
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
,D/dalvikvm( 1202): GC_CONCURRENT freed 1658K, 35% free 11273K/17224K, paused 4ms+6ms, total 67ms
,I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1541): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1541
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=3993 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
I/LaunchCheckinHandler( 1018): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,132
,I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/DEBUG   ( 1541): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
,D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SundryService( 1541): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1541): Received shoulder tap
I/ActivityManager( 1018): Activity reported stop, but no longer stopping: ActivityRecord{42721da8 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/WaitableIntentService( 1541): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,D/GetNotificationsWS( 1541): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1541): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1541): ServiceHandler.handleMessage: mWaitCount=2
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4006 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
W/PhenotypeConfigurator( 1202): Server returned 404
,D/dalvikvm( 3993): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f123e0, skipping init
I/openssl ( 3993): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3993): Crypto mode 0 already enabled
,I/ActivityManager( 1018): Killing 3826:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/DictionaryProvider:UpdateHandler( 1188): A file was downloaded but it can't be opened
E/DictionaryProvider:UpdateHandler( 1188): java.io.FileNotFoundException: No such file or directory
E/DictionaryProvider:UpdateHandler( 1188): 	at android.database.DatabaseUtils.readExceptionWithFileNotFoundExceptionFromParcel(DatabaseUtils.java:146)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentProviderProxy.openTypedAssetFile(ContentProviderNative.java:682)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentResolver.openTypedAssetFileDescriptor(ContentResolver.java:1063)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentResolver.openAssetFileDescriptor(ContentResolver.java:904)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentResolver.openFileDescriptor(ContentResolver.java:761)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentResolver.openFileDescriptor(ContentResolver.java:716)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.app.DownloadManager.openDownloadedFile(DownloadManager.java:1018)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.DownloadManagerWrapper.openDownloadedFile(DownloadManagerWrapper.java:72)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.UpdateHandler.handleDownloadedFile(UpdateHandler.java:520)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.UpdateHandler.downloadFinished(UpdateHandler.java:439)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.DictionaryService.dispatchBroadcast(DictionaryService.java:182)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.DictionaryService.access$000(DictionaryService.java:52)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.DictionaryService$1.run(DictionaryService.java:160)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.lang.Thread.run(Thread.java:841)
,E/DictionaryProvider:UpdateHandler( 1188): A file was downloaded but it can't be opened
E/DictionaryProvider:UpdateHandler( 1188): java.io.FileNotFoundException: No such file or directory
E/DictionaryProvider:UpdateHandler( 1188): 	at android.database.DatabaseUtils.readExceptionWithFileNotFoundExceptionFromParcel(DatabaseUtils.java:146)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentProviderProxy.openTypedAssetFile(ContentProviderNative.java:682)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentResolver.openTypedAssetFileDescriptor(ContentResolver.java:1063)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentResolver.openAssetFileDescriptor(ContentResolver.java:904)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentResolver.openFileDescriptor(ContentResolver.java:761)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.content.ContentResolver.openFileDescriptor(ContentResolver.java:716)
E/DictionaryProvider:UpdateHandler( 1188): 	at android.app.DownloadManager.openDownloadedFile(DownloadManager.java:1018)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.DownloadManagerWrapper.openDownloadedFile(DownloadManagerWrapper.java:72)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.UpdateHandler.handleDownloadedFile(UpdateHandler.java:520)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.UpdateHandler.downloadFinished(UpdateHandler.java:439)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.DictionaryService.dispatchBroadcast(DictionaryService.java:182)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.DictionaryService.access$000(DictionaryService.java:52)
E/DictionaryProvider:UpdateHandler( 1188): 	at com.android.inputmethod.dictionarypack.DictionaryService$1.run(DictionaryService.java:160)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DictionaryProvider:UpdateHandler( 1188): 	at java.lang.Thread.run(Thread.java:841)
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1283): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1283): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1283): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1283): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/openssl ( 3993): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3993): Crypto mode 0 already enabled
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451923569
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451923569
,I/Babel   ( 4006): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4006): MmsConfig.loadMmsSettings
,I/Babel   ( 4006): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4006): MmsConfig.loadFromDatabase
,E/Babel   ( 4006): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4006): MmsConfig.loadFromResources
,E/Babel   ( 4006): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4006): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,D/dalvikvm( 1018): GC_EXPLICIT freed 722K, 65% free 17882K/50512K, paused 4ms+11ms, total 96ms
,W/Settings( 4006): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4040 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,E/AppDataSearchClient( 1188): GetCorpusHandlesRegisteredForIME failed.
E/AppDataSearchClient( 1188): android.os.RemoteException
E/AppDataSearchClient( 1188): 	at com.google.android.gms.internal.dg.getSearchService(Unknown Source)
E/AppDataSearchClient( 1188): 	at com.google.android.gms.appdatasearch.AppDataSearchClient.getCorpusHandlesRegisteredForIME(Unknown Source)
E/AppDataSearchClient( 1188): 	at com.android.inputmethod.latin.amanatto.AmanattoDataUpdaterHelper$3.run(AmanattoDataUpdaterHelper.java:163)
E/AppDataSearchClient( 1188): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AppDataSearchClient( 1188): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AppDataSearchClient( 1188): 	at java.lang.Thread.run(Thread.java:841)
E/AppDataSearchClient( 1188): 	at com.android.inputmethod.latin.amanatto.AmanattoDataUpdaterHelper$BackgroundThreadFactory$1.run(AmanattoDataUpdaterHelper.java:68)
E/AppDataSearchClient( 1188): Caused by: java.lang.IllegalStateException: Not connected. Call connect() and wait for onConnected() to be called.
E/AppDataSearchClient( 1188): 	at com.google.android.gms.internal.eg.bU(Unknown Source)
E/AppDataSearchClient( 1188): 	at com.google.android.gms.internal.eg.bV(Unknown Source)
E/AppDataSearchClient( 1188): 	... 7 more
,E/AmanattoDataUpdater( 1188): Cannot get corpus handles.
,D/MMApiWSBase( 1541): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1541): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
I/GCM     ( 1343): Message from null null
,D/CCE     ( 1541): AppWSProxy - sendAIDLWSResponse() sending reponse
,E/GCM     ( 1343): Dropping message from null
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451923570
,W/dalvikvm( 4040): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4040): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 4040): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4040): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4040): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4040): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4040): install
,I/MultiDex( 4040): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4040): loading existing secondary dex files
,I/MultiDex( 4040): load found 3 secondary dex files
,I/MultiDex( 4040): install done
,D/Checkin ( 1541): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1541): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1541): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1541): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1541): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 1541): onHandleIntent(): isWaitEnabled=true
,D/WaitableIntentService( 1541): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1541): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 4040): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4040): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 4040): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4040): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4040): VFY: unable to resolve instance field 36
,D/dalvikvm( 4040): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 4040): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4040): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4040): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 4040): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4040): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 4040): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f12c70
,D/dalvikvm( 4040): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f12c70
,D/dalvikvm( 4040): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f12c70, skipping init
D/dalvikvm( 4040): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f12c70
D/dalvikvm( 4040): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f12c70
,V/JNIHelp ( 4040): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 4040): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41f12c70
,D/dalvikvm( 4040): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41f12c70
D/dalvikvm( 4040): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41f12c70
,D/dalvikvm( 4040): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f12c70
,D/dalvikvm( 2013): GC_CONCURRENT freed 1860K, 40% free 10354K/17224K, paused 3ms+2ms, total 26ms
,I/CalendarProvider2( 3954): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3954): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3925): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/ProviderInstaller( 4040): Installed default security provider GmsCore_OpenSSL
,D/AlertService( 3925): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/WearableService( 1202): callingUid 10022, callindPid: 1202
,E/MDM     ( 1202): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/dalvikvm( 4040): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
D/LocationInitializer( 1343): Restart initialization of location
W/dalvikvm( 4040): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4040): VFY: replacing opcode 0x6e at 0x00ce
D/AuthorizationBluetoothService( 2013): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2013): Proximity feature is not enabled.
,I/dalvikvm( 4040): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4040): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4040): VFY: replacing opcode 0x6e at 0x000d
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4040): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4040): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4040): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4040): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4040): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4040): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4040): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4040): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4040): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4040): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/dalvikvm( 4040): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
W/GCoreFlp( 1202): No location to return for getLastLocation()
,W/FusedLocationProvider( 1202): location=null
,I/PhenotypeConfigurator( 1202): Scheduling Phenotype for one-off execution 10936 seconds from now (1451923570516)
,D/GetConfigurationSnapshotOperation( 1202): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/dalvikvm( 1343): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1343): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1343): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 1541): GC_CONCURRENT freed 1818K, 38% free 10832K/17224K, paused 3ms+6ms, total 38ms
,D/MMApiWSBase( 1541): doRequest(): v1/us/devices/check resp length: 2314
,D/CCE     ( 1541): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1541): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.1030489269 for reqID:  error: None
,D/OtaWebService( 1541): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@4269d860 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@4241fff0
,D/OtaWebService( 1541): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"version\":\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\",\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"pollAfterSeconds\":21600,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): Level3 Library Nov 20 2013 18:09:31
D/OtaWebService( 1541): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@4269ef00 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@4241fff0
D/OtaWebService( 1541): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"version\":\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\",\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"pollAfterSeconds\":21600,\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
D/dalvikvm( 1343): GC_CONCURRENT freed 1734K, 30% free 12146K/17224K, paused 3ms+15ms, total 53ms
I/OtaApp  ( 1541): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update : 200 :  
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1541): [debug] > CusAndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
I/OtaApp  ( 1541): [info] > Next Polling is scheduled at 359 mins from now
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1541): [info] > CusSM.handleNewVersion: was notified of a new version : src Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU: dest Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU: current Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU: size 12503823
D/PollingManager( 1541): registerApp(): cUsPollingService
D/PollingManager( 1541): registerApp(): shortest interval is 21599000
D/PollingManager( 1541): Polling alarm set to expire at: 21833226 Current Time: 234227
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 1541): [info] > Device is NOT rooted. persist.qe=qe 0/0
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
D/DrmWidevineDash(  278): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/QSEECOMAPI: (  278): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/QSEECOMAPI: (  278): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  278): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  278): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  278): App is not loaded in QSEE
E/OtaApp  ( 1541): [error] > UpgradeSource.isUpgradeAcceptable succeeded 
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
I/PhenotypeFlagCommitter( 1202): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
D/dalvikvm( 1343): DexOpt: --- BEGIN 'ads-608627430.jar' (bootstrap=0) ---
D/OtaApp  ( 1541): [debug] > prevDestVersion = Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU
W/OtaApp  ( 1541): [warn] > CusSM.handleNewVersion: already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
E/OtaApp  ( 1541): [error] > CusSM.failNotify: notification failed from repository upgrade for reason already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK; additional information: polling initiated upgrade
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1541): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1451923570663, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 1541): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1451923570683, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/QSEECOMAPI: (  278): Loaded image: APP id = 3
,D/DrmWidevineDash(  278): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb536d000
,E/DrmWidevineDash(  278): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb536d000
,D/DrmWidevineDash(  278): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  278): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  278): calling OEMCrypto_IsKeyboxValid...
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
,D/OtaApp  ( 1541): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  NotifiedBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EUBlur_Version.21.11.56.peregrine_reteu.reteuall.en.EURepository: upgrade; Location: null; AddOnInfo: polling initiated upgrade1451923570722false
,D/DrmWidevineDash(  278): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  278): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,I/GoogleURLConnFactory( 1202): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/dalvikvm( 4040): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 4040): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 4040): VFY: replacing opcode 0x6e at 0x003d
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/NativeLibraryUtils( 4040): Install completed successfully. count=14 extracted=0
,I/dalvikvm( 1541): Jit: resizing JitTable from 4096 to 8192
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; src: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; dest: Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU; upgradeSource:upgrade; Repository: upgrade; Location: null; AddOnInfo: polling initiated upgrade; reportingTag: TRIGGER-POLLING,peregrine_reteu_1411553875137; trackingId: 2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007; metaDataVersion: 1410862052; ro.carrier: reteu. time: 1451923570
,I/OtaApp  ( 1541): [info] > retrieving device info from cce
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
W/dalvikvm( 4040): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,W/dalvikvm( 4040): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/MMApiWSBase( 1541): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1541): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
,D/CCE     ( 1541): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/BSUtils ( 1541): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/dalvikvm( 4040): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=1787173311
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
I/dalvikvm( 4040): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 4040): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 4040): VFY: replacing opcode 0x6e at 0x00bb
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/GoogleURLConnFactory( 4040): Using platform SSLCertificateSocketFactory
I/OtaApp  ( 1541): [info] > Received deviceInfo from cce : 
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1541): [info] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: check_for_update handle new version returned false
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaWebService( 1541): [info] > Received web service call for request :v1/us/devices/state
,D/OtaApp  ( 1541): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
D/OtaApp  ( 1541): [debug] > OTAUpgradeSource.handleMMApiCheckForUpdateResponse: authoritative response from BOTA ERR_NOTFOUND
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaWebService( 1541): [debug] > appending web service request to serviceHandler
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/us/devices/state)
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1541): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: server told to :wait
,D/OtaWebService( 1541): [debug] > appending web service response to serviceHandler
,D/OtaWebService( 1541): [debug] > Removing request :v1/us/devices/check from queue
,D/Checkin ( 1541): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1541): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1541): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1541): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1541): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1541): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1541): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1541): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 4075): DexOpt: load 4ms, verify+opt 12ms, 192820 bytes
,D/dalvikvm( 1343): DexOpt: --- END 'ads-608627430.jar' (success) ---
,D/dalvikvm( 1343): DEX prep '/data/data/com.google.android.gms/cache/ads-608627430.jar': unzip in 0ms, rewrite 230ms
,I/MMApiWSBase( 1541): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/state.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 4040): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422cec48
D/dalvikvm( 4040): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422cec48
,D/dalvikvm( 4040): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x422cec48, skipping init
,D/dalvikvm( 1202): GC_CONCURRENT freed 1486K, 33% free 11707K/17224K, paused 4ms+8ms, total 37ms
,W/Settings( 4040): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Babel   ( 4006): Account registration complete:Redacted-21
,D/dalvikvm( 4040): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4090): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4040): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4040): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 80ms
,I/Adreno-EGL( 4040): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4040): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4040): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4040): Local Branch: 
I/Adreno-EGL( 4040): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4040): Local Patches: NONE
I/Adreno-EGL( 4040): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4040): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4040): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4040): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4040): Local Branch: 
I/Adreno-EGL( 4040): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4040): Local Patches: NONE
I/Adreno-EGL( 4040): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/WVCdm   (  278): CdmEngine::OpenSession
,D/DrmWidevineDash(  278): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  278): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  278): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  278): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  278): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  278): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  278): PrepareKeyRequest: nonce=666880349
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  278): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  278): CdmEngine::CloseSession
,D/DrmWidevineDash(  278): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  278): OEMCrypto_CloseSession returns 0
,I/Choreographer( 3533): Skipped 769 frames!  The application may be doing too much work on its main thread.
,W/IInputConnectionWrapper( 3533): showStatusIcon on inactive InputConnection
,I/chromium( 3533): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SFPerfTracer(  274):      triggers: (rate: 2:30) (compose: 0:4) (post: 0:1) (render: 0:4) (0:107 frames) (1:538)
,D/SFPerfTracer(  274):        layers: (0:13) (FocusedStackFrame: 0:10)* (StatusBar: 0:203)* (NavigationBar: 0:37)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 1:4)* 
,I/Adreno-EGL( 4040): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4040): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4040): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4040): Local Branch: 
I/Adreno-EGL( 4040): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4040): Local Patches: NONE
I/Adreno-EGL( 4040): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4040): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4040): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4040): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4040): Local Branch: 
I/Adreno-EGL( 4040): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4040): Local Patches: NONE
I/Adreno-EGL( 4040): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1343): Classify the device as Phone.
,I/CheckinTask( 1343): Sending checkin request (12642 bytes)
,I/CheckinRequestBuilder( 1343): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1343): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1343): Classify the device as Phone.
,I/CheckinTask( 1343): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1343): Checking schedule, now: 1451923573627 next: 1452516643591
,I/CheckinService( 1343): active receiver: disabled
,D/dalvikvm( 1343): GC_CONCURRENT freed 2004K, 30% free 12072K/17224K, paused 6ms+5ms, total 47ms
,D/CheckinService( 1343): Recording last checkin time for package unspecified as 1451923573647
,D/GCM     ( 2013): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 3867): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 3925): no sender configured
,D/AlertService( 3925): Beginning updateAlertNotification
,D/AlertService( 3925): No fired or scheduled alerts
,D/AlertService( 3925): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3925): No events found starting within 1 week.
I/ActivityManager( 1018): Killing 3853:com.google.android.setupwizard/u0a41 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 3799:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1018): DelayedCaptiveCheckState{ when=-4ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1018): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1018): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager( 1018): Killing 3867:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1018): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1018): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 1018): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1018): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1018): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4126 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/Launcher( 1295): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/Launcher( 1295): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/Launcher( 1295): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/Launcher( 1295): Deferring update until onResume
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
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,I/ActivityManager( 1018): Killing 3076:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1018):   Scheme: "mmsto"
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1018): GC_CONCURRENT freed 2035K, 65% free 18073K/50512K, paused 4ms+10ms, total 86ms
D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 57ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 55ms
D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 55ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 57ms
,I/ActivityManager( 1018): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4155 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ContactLocale( 4126): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/InternalIcingCorporaPro( 2181): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4171 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
I/ActivityManager( 1018): Killing 3954:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2181): UpdateCorporaTask done [took 38 ms] updated apps [took 37 ms] 
,I/GCoreNlp( 1202): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4191 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager( 1018): Killing 3975:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 4171): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/iu.UploadsManager( 4171): End new media; added: 0, uploading: 0, time: 43 ms
,I/iu.Environment( 4171): update battery state; isPlugged? true*
,I/iu.Environment( 4171): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.FingerprintManager( 4171): Start processing all media
,I/iu.FingerprintManager( 4171): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 4171): Start processing media store URI: content://media/external/video/media
I/dalvikvm( 4191): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4191): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x000e
,I/iu.FingerprintManager( 4171): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 4171): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 4171): Finished generating fingerprints; 0.018 seconds
,I/iu.FingerprintManager( 4171):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/Finsky  ( 4191): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4191): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4191): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4191): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4191): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4191): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/dalvikvm( 4191): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4191): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4191): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4191): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4191): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4191): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4191): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4191): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4191): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4191): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4191): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4191): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4191): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 4191): Skipping gmscore version check
,D/Finsky  ( 4191): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4191): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4191): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4191): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x0017
,D/PackageBroadcastService( 1343): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/Finsky  ( 4191): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/InternalIcingCorporaPro( 2181): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 1018): Killing 3942:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1343): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1343): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1343): updateResources: need to parse f{com.google.android.gms}
,I/InternalIcingCorporaPro( 2181): UpdateCorporaTask done [took 301 ms] updated apps [took 301 ms] 
,V/AlarmManager( 1018): sending alarm Alarm{42806508 type 0 com.android.vending}
,D/Finsky  ( 4191): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 4191): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4191): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4191): VFY: replacing opcode 0x62 at 0x0038
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/Icing   ( 1343): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1343): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451923580
,I/qtaguid ( 4191): Failed write_ctrl(u 67) res=-1 errno=22
I/qtaguid ( 4191): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4191): untagSocket(67) failed with errno -22
,D/Finsky  ( 4191): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4191): Total arena pages for JIT: 11
,I/dalvikvm( 4191): Total arena pages for JIT: 12
I/dalvikvm( 4191): Total arena pages for JIT: 13
,I/dalvikvm( 4191): Total arena pages for JIT: 14
,I/qtaguid ( 4191): Failed write_ctrl(u 67) res=-1 errno=22
I/qtaguid ( 4191): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4191): untagSocket(67) failed with errno -22
,D/dalvikvm( 4191): GC_FOR_ALLOC freed 4591K, 29% free 12249K/17224K, paused 30ms, total 32ms
,D/dalvikvm( 4191): GC_FOR_ALLOC freed 1086K, 28% free 12470K/17224K, paused 20ms, total 21ms
,D/dalvikvm( 4191): GC_CONCURRENT freed 1126K, 23% free 13392K/17224K, paused 3ms+3ms, total 31ms
,D/dalvikvm( 4191): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 4191): GC_CONCURRENT freed 1196K, 18% free 14243K/17224K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 4191): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4191): GC_CONCURRENT freed 1500K, 15% free 14791K/17224K, paused 3ms+3ms, total 48ms
,D/dalvikvm( 4191): WAIT_FOR_CONCURRENT_GC blocked 22ms
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 4191): Failed write_ctrl(u 67) res=-1 errno=22
,I/qtaguid ( 4191): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4191): untagSocket(67) failed with errno -22
,D/Finsky  ( 4191): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.googlequicksearchbox to true
,D/Finsky  ( 4191): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.googlequicksearchbox from  to d_AAAAAAADF8w=
,D/Finsky  ( 4191): [1] LibraryUtils.isAvailable: com.quickoffice.android available because owned, overriding [restriction=7].
,D/Finsky  ( 4191): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1018): sending alarm Alarm{42750cf0 type 0 com.android.vending}
,D/dalvikvm( 1018): GC_EXPLICIT freed 1082K, 65% free 17952K/50512K, paused 4ms+9ms, total 88ms
,D/WearableService( 1202): callingUid 10022, callindPid: 1202
,D/DeviceConnectionService( 1202): client connected with version: 8296000
,D/Finsky  ( 4191): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/Finsky  ( 4191): [358] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4191): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/Finsky  ( 4191): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4191): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/dalvikvm( 4191): GC_CONCURRENT freed 1476K, 11% free 15362K/17224K, paused 8ms+3ms, total 64ms
,D/dalvikvm( 4191): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 2013): GC_EXPLICIT freed 794K, 40% free 10352K/17224K, paused 2ms+5ms, total 29ms
,D/MMApiWSBase( 1541): doRequest(): v1/us/devices/state resp length: 2224
,D/CCE     ( 1541): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1541): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.-2123477995 for reqID:  error: None
,D/OtaWebService( 1541): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@4258e8d0 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@42160430
,D/OtaWebService( 1541): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1541): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@4206a000 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@42160430
,D/OtaWebService( 1541): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaApp  ( 1541): [debug] > Inside handleMMApiUpgradeStatusResponse
,D/OtaApp  ( 1541): [debug] > exec delete from status where _id=1
,D/OtaApp  ( 1541): [debug] > stopTimer, cancel()
,D/OtaApp  ( 1541): [debug] > handleMMApiUpgradeStatusResponse server told to : continue
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
,D/OtaApp  ( 1541): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  ResultBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EUBlur_Version.21.11.56.peregrine_reteu.reteuall.en.EUalready working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK1451923589656false
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; src: Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; dest: Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU; upgradeSource:upgrade; already working on version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU with status RS_TEMP_OK; reportingTag: TRIGGER-POLLING,peregrine_reteu_1411553875137; trackingId: 2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007; metaDataVersion: 1410862052; ro.carrier: reteu. time: 1451923570
,I/OtaApp  ( 1541): [info] > retrieving device info from cce
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,I/BSUtils ( 1541): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/OtaApp  ( 1541): [info] > Received deviceInfo from cce : 
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaWebService( 1541): [info] > Received web service call for request :v1/us/devices/state
,D/dalvikvm( 1541): GC_CONCURRENT freed 2002K, 37% free 10877K/17224K, paused 4ms+3ms, total 55ms
,D/dalvikvm( 1541): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1541): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/OtaWebService( 1541): [debug] > appending web service request to serviceHandler
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1541): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1541): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1541): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1541
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: already sending status
D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: already sending status
D/OtaWebService( 1541): [debug] > appending web service response to serviceHandler
D/OtaWebService( 1541): [debug] > Removing request :v1/us/devices/state from queue
D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/us/devices/state)
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
I/MMApiWSBase( 1541): doRequest(): url: https://api.svcmot.com:443/v1/us/devices/state.json/1135300315450105856?appId=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/MMApiWSBase( 1541): doRequest(): v1/us/devices/state resp length: 2224
,D/CCE     ( 1541): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 1541): AppWSProxy - sendWSResponse(): sending response to com.motorola.ccc.ota.webservice.response.-210555329 for reqID:  error: None
,D/OtaWebService( 1541): [debug] > WebService.checkAndInvokeRetryHandler(): invoking retry handler: com.motorola.ccc.ota.webservice.InternalRetryHandler@426cc1f0 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@420825c0
,D/OtaWebService( 1541): [debug] > InternalRetryHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaWebService( 1541): [debug] > WebService.checkAndInvokeResponseHandler(): invoking response handler: com.motorola.ccc.ota.webservice.InternalResponseHandler@4208dad8 with response com.motorola.ccc.ota.webservice.dataobjects.WebResponse@420825c0
,D/OtaWebService( 1541): [debug] > InternalResponseHandler:onTransact() response string from WebService{"response":{"error":"None","statusCode":200,"payload":"{\"metaDataVersion\":\"1410862052\",\"metaData\":\"{\\\"metaVersion\\\":1410862052,\\\"version\\\":\\\"Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU\\\",\\\"minVersion\\\":\\\"Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU\\\",\\\"forced\\\":\\\"true\\\",\\\"releaseNotes\\\":\\\"\\\",\\\"flavour\\\":\\\"\\\",\\\"size\\\":12503823,\\\"extraSpace\\\":0,\\\"annoy\\\":\\\"60\\\",\\\"wifionly\\\":\\\"false\\\",\\\"fingerprint\\\":\\\"motorola\/peregrine_reteu\/peregrine:4.4.4\/KXB21.14-L1.46\/42:user\/release-keys\\\",\\\"downloadUrl\\\":\\\"\\\",\\\"installTime\\\":10,\\\"serviceControlEnabled\\\":\\\"true\\\",\\\"serviceTimeoutSeconds\\\":60,\\\"continueOnServiceError\\\":\\\"true\\\",\\\"upgradeNotification\\\":\\\"\\\\u003cp\\\\u003e\\\\n    \\\\u003cstrong\\\\u003e\\\\u003ca href\\\\u003d http:\/\/motorola.com\/motog_4g\/releasenotes\/4.4.4\/mr1\/ \\\\u003eInformation\\\\u003c\/a\\\\u003e\\\\u003c\/strong\\\\u003e\\\\n\\\\u003c\/p\\\\u003e\\\",\\\"preInstallNotes\\\":\\\"\\\",\\\"postInstallNotes\\\":\\\"\\\",\\\"packageID\\\":\\\"delta-ota-Blur_Version.21.1.46-21.11.56.peregrine_reteu.reteuall.en.EU.zip.4c75e482-0e65-4c1a-a18b-2e0638ffbd80\\\",\\\"reportingTag\\\":\\\"TRIGGER-POLLING,peregrine_reteu_1411553875137\\\",\\\"trackingId\\\":\\\"2214d981-17a5-4984-b273-ceaabf23e34c:1411728159007\\\",\\\"showPreDownloadDialog\\\":\\\"true\\\",\\\"showDownloadOptions\\\":\\\"false\\\",\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440,\\\"uiWorkflowControl\\\":{\\\"polling\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"setup\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"user\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440},\\\"notification\\\":{\\\"wifionly\\\":false,\\\"forced\\\":true,\\\"showPreDownloadDialog\\\":true,\\\"showDownloadOptions\\\":true,\\\"preDownloadNotificationExpiryMins\\\":1440,\\\"preInstallNotificationExpiryMins\\\":1440}},\\\"downloadOptionsNotes\\\":\\\"\\\"}\",\"status\":\"OTA_OK\",\"status_description\":\"{\\\"code\\\":\\\"OTA_OK\\\",\\\"description\\\":\\\"Everything is okay. Life is good!\\\"}\"}\n","errorText":""}}
,D/OtaApp  ( 1541): [debug] > Inside handleMMApiUpgradeStatusResponse
,D/OtaApp  ( 1541): [debug] > exec delete from status where _id=2
,D/OtaApp  ( 1541): [debug] > stopTimer, have stoped, do nothing
,D/OtaApp  ( 1541): [debug] > handleMMApiUpgradeStatusResponse server told to : continue
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1541): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1541): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1541): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1541): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1018): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1541
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaWebService( 1541): [debug] > appending web service response to serviceHandler
,D/OtaWebService( 1541): [debug] > Removing request :v1/us/devices/state from queue
,D/OtaWebService( 1541): [debug] > No pending web request. shutdown webservice
,I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaWebService( 1541): [info] > Stopping webservice android service
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42806450 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{42875508 type 0 com.android.vending}
,D/Finsky  ( 4191): [348] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4191): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1018): sending alarm Alarm{42805d78 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{421713c8 type 2 android}
,E/ActivityThread( 1343): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 291775, reason: UserStart
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
,V/AlarmManager( 1018): sending alarm Alarm{427d7448 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{427bbf68 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{42792000 type 3 android}
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
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  273): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 8
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
,V/AlarmManager( 1018): sending alarm Alarm{4206ba28 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4271e118 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{44576fc0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{42770ae0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4253f708 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4226fe80 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42803598 type 1 com.android.deskclock}
,I/LaunchCheckinHandler( 1018): cleanup(): cleared. Last call was 509706 ms ago
,I/ActivityManager( 1018): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4336 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1018): Killing 3925:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,V/AlarmManager( 1018): sending alarm Alarm{445ccad8 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4323d368 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{428cfd18 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{428dd7e0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{42815be8 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{43c81670 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{42800aa0 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1018): sending alarm Alarm{427ff630 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,D/ConnectivityService( 1018): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1283): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1283): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1283): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
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
,V/AlarmManager( 1018): sending alarm Alarm{4201b8c0 type 3 android}
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{420c5be0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{427560e0 type 3 android}
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
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{42891e08 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{42060c28 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{43a24638 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4321eb98 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{427713d0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{4455b0d0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4201b970 type 1 com.android.deskclock}
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
,V/AlarmManager( 1018): sending alarm Alarm{439b9440 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{428b99d0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{420c5190 type 3 android}
,I/ProcessStatsService( 1018): Prepared write state in 15ms
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2016-01-03-15-37-00.bin
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
,V/AlarmManager( 1018): sending alarm Alarm{432b97d0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{43983ff0 type 3 android}
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
,V/AlarmManager( 1018): sending alarm Alarm{43abf760 type 3 android}
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
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4382): 
D/AndroidRuntime( 4382): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4382): CheckJNI is OFF
D/dalvikvm( 4382): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4382): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4382): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4382): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4382): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4382): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4382): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4382): failed to load memtrack module: -2
D/AndroidRuntime( 4382): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10510 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 3533:com.test.thalitest/u0a510 (adj 9): stop com.test.thalitest
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{445b1120 u0 com.test.thalitest/.MainActivity t3}
I/WindowState( 1018): WIN DEATH: Window{446516c0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1018): Client connection lost with reason: 4
W/PackageSettings( 1018): Skipping PackageSetting{421d0d38 com.example.hello/10509} due to missing metadata
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10510 user=0: pkg removed
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{445b1120 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{445b1120 u0 com.test.thalitest/.MainActivity t3 f}
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 2149): GC_EXPLICIT freed 6283K, 44% free 9739K/17224K, paused 3ms+6ms, total 64ms
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451925366
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
D/dalvikvm( 2181): GC_EXPLICIT freed 2985K, 43% free 9821K/17224K, paused 2ms+3ms, total 116ms
D/dalvikvm( 1295): GC_EXPLICIT freed 2955K, 33% free 11631K/17224K, paused 1ms+5ms, total 120ms
D/dalvikvm( 1343): GC_EXPLICIT freed 1825K, 31% free 12035K/17224K, paused 3ms+12ms, total 167ms
W/SQLiteConnectionPool( 1343): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/dalvikvm( 1018): GC_EXPLICIT freed 1849K, 65% free 18116K/50512K, paused 5ms+11ms, total 128ms
I/Launcher( 1295): Deferring update until onResume
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
D/VoicemailCleanupService( 4126): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/InternalIcingCorporaPro( 2181): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/Launcher( 1295): Deferring update until onResume
I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4414 uid=10059 gids={50059, 3003, 1028, 1015}
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451925367
I/InternalIcingCorporaPro( 2181): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10510 #1
D/dalvikvm( 1018): GC_EXPLICIT freed 782K, 65% free 18068K/50512K, paused 14ms+15ms, total 252ms
D/AndroidRuntime( 4382): Shutting down VM
D/dalvikvm( 4382): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
W/ActiveOrDefaultContextProvider( 4414): Missing scope.enter somewhere. Returning default context
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4436 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1018): Killing 4040:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+4ms, total 23ms
W/GAV2    ( 4414): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
W/ContextImpl( 4436): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4191): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4191): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4191): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1343): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1343): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1343): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1343): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1343): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1343): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1343): disk I/O error (code 3850)
E/DriveAsyncService( 1343): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1343): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1343): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1343): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1343): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1343): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1343): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1343): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1343): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1343): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1343): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1343): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1343): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1343): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 1343): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1343): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1343): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1343): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1343): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1343): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1343): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1343): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1343): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1343): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1343): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1343): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/PhenotypeInitializer( 1343): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1343): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 1343): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 1343): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1343): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1343): 	at android.os.Looper.loop(Looper.java:136)
E/PhenotypeInitializer( 1343): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1343): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2013): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2013): Shutting down VM
D/ChimeraCfgMgr( 1343): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1343): Module APK com.google.android.play.games already loaded
W/dalvikvm( 2013): threadid=1: thread exiting with uncaught exception (group=0x4163fd40)
E/ClearPendingStateOp( 1343): Runtime exception while performing operation
E/ClearPendingStateOp( 1343): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1343): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 1343): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1343): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 1343): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
E/ClearPendingStateOp( 1343): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1343): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1343): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1343): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1343): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1343): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1343): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1343): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1343): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1343): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1343): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1343): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1343): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1343): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1343): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1343): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1343): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1343): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1343): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1343): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1343): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1343): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 1343): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1343): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 1343): 	at android.content.ContentResolver.delete(ContentResolver.java:1282)
F/ClearPendingStateOp( 1343): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1343): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1343): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1343): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1343): 	at java.lang.Thread.run(Thread.java:841)
E/GMPM-SVC( 1343): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteOpenHelper( 1343): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1343): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1343): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 1343): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1343): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1343): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1343): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1343): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1343): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1343): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1343): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 1343): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2013): FATAL EXCEPTION: main
E/AndroidRuntime( 2013): Process: com.google.process.gapps, PID: 2013
E/AndroidRuntime( 2013): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2013): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 2013): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 2013): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 2013): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2013): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2013): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 2013): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2013): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2013): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 2013): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 2013): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2013): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2013): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2013): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 2013): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2013): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2013): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 2013): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2013): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2013): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2013): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 2013): 	... 10 more
E/SharedPreferencesImpl( 1343): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
W/SQLiteOpenHelper( 1343): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1343): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1343): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1343): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1343): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 1343): threadid=49: thread exiting with uncaught exception (group=0x4163fd40)
I/Icing   ( 1343): doRemovePackageData com.test.thalitest
E/SQLiteLog( 1343): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1343): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1343): threadid=53: thread exiting with uncaught exception (group=0x4163fd40)
I/Process ( 1343): Sending signal. PID: 1343 SIG: 9
E/DropBoxManagerService( 1018): Can't write: system_app_wtf
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
I/Process ( 2013): Sending signal. PID: 2013 SIG: 9
E/DropBoxManagerService( 1018): Can't write: system_app_crash
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
E/SQLiteDatabase( 4436): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4436): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4436): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4436): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4436): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4436): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4436): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4436): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4436): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4436): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4436): threadid=11: thread exiting with uncaught exception (group=0x4163fd40)
E/AndroidRuntime( 4436): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4436): Process: com.android.keychain, PID: 4436
E/AndroidRuntime( 4436): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4436): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4436): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4436): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4436): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4436): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4436): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4436): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4436): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1018): Process com.google.process.gapps (pid 2013) has died.
D/WifiService( 1018): Client connection lost with reason: 4
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
I/ActivityManager( 1018): Process com.google.android.gms (pid 1343) has died.
D/WifiService( 1018): Client connection lost with reason: 4
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10993ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10993ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10993ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10993ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10992ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 10992ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 20992ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 30992ms
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 40992ms
I/Process ( 4436): Sending signal. PID: 4436 SIG: 9
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
I/ActivityManager( 1018): Process com.android.keychain (pid 4436) has died.
W/ActivityManager( 1018): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 50984ms

```
