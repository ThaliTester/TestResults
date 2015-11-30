#### Test 519863409bc5c94_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{43bc99d8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3568): 
D/AndroidRuntime( 3568): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3568): CheckJNI is OFF
D/dalvikvm( 3568): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3568): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3568): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3568): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3568): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3568): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3568): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3568): failed to load memtrack module: -2
D/AndroidRuntime( 3568): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3568
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3584 uid=10418 gids={50418, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3568): Shutting down VM
D/dalvikvm( 3568): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 24ms
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 24ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
V/WebViewChromiumFactoryProvider( 3584): Binding Chromium to main looper Looper (main, tid 1) {41f3b9d8}
I/LibraryLoader( 3584): Expected native library version number "",actual native library version number ""
I/chromium( 3584): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3584): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43bc47a8:true
D/BluetoothAdapter( 3584): 1106575336: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3584): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3584): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3584): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3584): Local Branch: 
I/Adreno-EGL( 3584): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3584): Local Patches: NONE
I/Adreno-EGL( 3584): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3584): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3584): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3584): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3584): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3584): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3584): VFY: unable to resolve virtual method 208: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3584): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3584): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3584): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3584): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3584): VFY: unable to resolve virtual method 266: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3584): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3584): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3584): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3584): VFY: unable to resolve virtual method 224: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3584): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3584): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3584): VFY: unable to resolve virtual method 229: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3584): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3584): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3584): Enabling debug mode 0
,W/AwContents( 3584): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,420
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +391ms (total +420ms)
W/AwContents( 3584): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3584): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3584): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3584): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f3fe88
,D/dalvikvm( 3584): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f3fe88
D/jxcore_app_log( 3584): JniHelper::setJavaVM(0x41587fa8), pthread_self() = 1613920656
,D/JX-Cordova( 3584): jxcore cordova android initializing
,D/dalvikvm( 3584): GC_CONCURRENT freed 2833K, 17% free 14356K/17224K, paused 4ms+2ms, total 62ms
,D/dalvikvm( 3584): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 3584): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 216K, 17% free 14334K/17224K, paused 26ms, total 27ms
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 188K, 17% free 14363K/17224K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3584): Grow heap (frag case) to 16.199MB for 146998-byte allocation
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 258K, 18% free 14412K/17368K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3584): Grow heap (frag case) to 16.316MB for 220492-byte allocation
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 375K, 18% free 14487K/17584K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3584): Grow heap (frag case) to 16.496MB for 330734-byte allocation
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 582K, 19% free 14611K/17908K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3584): Grow heap (frag case) to 16.774MB for 496096-byte allocation
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 885K, 20% free 14790K/18396K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3584): Grow heap (frag case) to 17.185MB for 744140-byte allocation
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 1309K, 22% free 15051K/19124K, paused 28ms, total 28ms
,D/dalvikvm( 3584): GC_CONCURRENT freed 1673K, 20% free 15426K/19124K, paused 3ms+3ms, total 35ms
,D/dalvikvm( 3584): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 415K, 20% free 15389K/19124K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3584): Grow heap (frag case) to 18.658MB for 1674304-byte allocation
,D/dalvikvm( 3584): GC_CONCURRENT freed 1757K, 24% free 15979K/20760K, paused 1ms+7ms, total 52ms
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 1373K, 23% free 16045K/20760K, paused 31ms, total 31ms
,I/dalvikvm-heap( 3584): Grow heap (frag case) to 20.096MB for 2511452-byte allocation
,D/dalvikvm( 3584): GC_CONCURRENT freed 1946K, 28% free 16736K/23216K, paused 5ms+4ms, total 49ms
,D/dalvikvm( 3584): GC_CONCURRENT freed 2329K, 27% free 16986K/23216K, paused 1ms+7ms, total 44ms
,D/dalvikvm( 3584): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 3584): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 702K, 28% free 16754K/23216K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3584): Grow heap (frag case) to 21.986MB for 3767174-byte allocation
,D/dalvikvm( 3584): GC_CONCURRENT freed 261K, 25% free 20440K/26896K, paused 5ms+3ms, total 43ms
,D/dalvikvm( 3584): GC_FOR_ALLOC freed 2799K, 34% free 17975K/26896K, paused 27ms, total 27ms
,W/jxcore-log( 3584): Initializing JXcore engine
,W/jxcore-log( 3584): JXcore engine is ready
,D/dalvikvm( 3584): GC_CONCURRENT freed 339K, 24% free 20612K/26896K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 3584): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 3584): Starting JXcore engine
,W/jxcore-log( 3584): Platform android
W/jxcore-log( 3584): 
,W/jxcore-log( 3584): Process ARCH arm
W/jxcore-log( 3584): 
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
,I/jxcore-log( 3584): JXcore Cordova bridge is ready!
I/jxcore-log( 3584): 
,W/jxcore-log( 3584): JXcore engine is started
,I/chromium( 3584): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3584): Toggling radios to true
I/jxcore-log( 3584): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService( 1019): Message: 1
D/BluetoothManagerService( 1019): MESSAGE_ENABLE: mBluetooth = null
,W/Settings( 1243): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1243): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiService( 1019): New client listening to asynchronous messages
D/WifiService( 1019): setWifiEnabled: true pid=3584, uid=10418
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1255): Active network info is not available
,I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3634 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,D/WifiStateMachine( 1019): setting operational mode to 1
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3584): Radios toggled
I/jxcore-log( 3584): 
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1255): Active network info is not available
,D/AdapterServiceConfig( 3634): Adding HeadsetService
D/AdapterServiceConfig( 3634): Adding A2dpService
,D/AdapterServiceConfig( 3634): Adding HidService
D/AdapterServiceConfig( 3634): Adding HealthService
D/AdapterServiceConfig( 3634): Adding PanService
D/AdapterServiceConfig( 3634): Adding GattService
,D/AdapterServiceConfig( 3634): Adding BluetoothMapService
,D/BluetoothAdapterService( 3634): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@436a9800:true
,D/BluetoothAdapterState( 3634): make
,I/BluetoothAdapterState( 3634): Entering OffState
,I/bluedroid( 3634): init
,I/bte_conf( 3634): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bluedroid( 3634): get_profile_interface socket
,I/GKI_LINUX( 3634): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3634): Address is:F4:F1:E1:5C:3B:E2
,I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3634): Name is: XT1039
,D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService( 1019): Message: 40
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
,I/bluedroid( 3634): config_hci_snoop_log
D/BluetoothManagerService( 1019): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothAdapterState( 3634): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3634): Setting state to 11
I/BluetoothAdapterState( 3634): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3634): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 1019): Message: 60
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothBondStateMachine( 3634): make
,D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3660 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BluetoothHeadset( 1019): Proxy object connected
D/HeadsetService( 3634): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3634): classInitNative: succeeds
D/HeadsetStateMachine( 3634): Version 1.6
D/HeadsetStateMachine( 3634): make
D/BluetoothHeadset( 1238): Proxy object connected
D/BluetoothHeadset( 1238): Proxy object connected
D/BluetoothHeadset( 1238): Proxy object connected
,I/BluetoothAdapterState( 3634): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3634): get_profile_interface handsfree
,D/BluetoothA2dp( 1019): Proxy object connected
D/A2dpService( 3634): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3634): classInitNative: succeeds
,V/Avrcp   ( 3634): make
,I/bluedroid( 3634): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 3634): classInitNative: succeeds
,D/A2dpStateMachine( 3634): make
,I/bluedroid( 3634): get_profile_interface a2dp
,I/GKI_LINUX( 3634): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3634): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3634): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3634): classInitNative: succeeds
,D/HidService( 3634): Received start request. Starting profile...
I/bluedroid( 3634): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3634): classInitNative: succeeds
,D/HealthService( 3634): Received start request. Starting profile...
,I/bluedroid( 3634): get_profile_interface health
,I/BluetoothPanServiceJni( 3634): classInitNative(L105): succeeds
,D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
D/PanService( 3634): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3634): initializeNative(L110): pan
,I/bluedroid( 3634): get_profile_interface pan
,D/BluetoothTethering( 1019): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothTethering( 1019): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@4349a7f0
,I/BtGatt.JNI( 3634): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 3634): handleDebugAction() action=null
D/BtGatt.GattService( 3634): Received start request. Starting profile...
D/BtGatt.GattService( 3634): start()
,I/bluedroid( 3634): get_profile_interface gatt
,D/BluetoothMapService( 3634): Received start request. Starting profile...
,D/BluetoothMapService( 3634): start()
,D/HeadsetPhoneState( 3634): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 3634): onSignalStrengthsChanged..for signal  prevSignal=0
,D/BluetoothAdapterService( 3634): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3634): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3634): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3634): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3634): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3634): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3634): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3634): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3634): enable
,I/bt_hci_bdroid( 3634): init
I/bt_vendor( 3634): bt-vendor : init
I/bt_hci_bdroid( 3634): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3634): userial_init
I/bt_hwcfg( 3634): Starting hciattach daemon
,I/bt_hwcfg( 3634): try to set false
I/bt_hwcfg( 3634): Starting hciattach daemon
,I/bt_hwcfg( 3634): try to set true
,I/bt_hci_bdroid( 3634): bt_hc_worker_thread started
,I/ActivityManager( 1019): Killing 3315:com.android.calendar/u0a7 (adj 15): empty #9
,I/qcom-bluetooth( 3694): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is add
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
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiService( 1019): New client listening to asynchronous messages
D/TCMD    (  437): NL - Read 1004 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is add
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
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,I/qcom-bluetooth( 3703): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/TCMD    (  437): NL - Read 1004 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,I/qcom-bluetooth( 3704): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/QsoftapCmd(  273): Got softap fwreload command we are passing on
,D/SoftapController(  273): Softap fwReload - Ok
D/CommandListener(  273): Setting iface cfg
D/CommandListener(  273): Trying to bring down wlan0
,I/qcom-bluetooth( 3706): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,I/qcom-bluetooth( 3707): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,I/qcom-bluetooth( 3708): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,D/WifiStateMachine( 1019): setWifiState: enabling
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1255): Active network info is not available
E/Diag_Lib( 3711): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3711): Setting internal use port to rmnet0
E/Diag_Lib( 3711):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
E/Diag_Lib( 3711): Failed on DIAG init
E/Diag_Lib( 3711): linux_qmi_qmux_if_client_get_proc_name: pid=3711, proc_name=hci_qcomm_init
E/Diag_Lib( 3711): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3711): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3711): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3711): qmi_client [3711]: successfully connected to server, attempt=1
E/Diag_Lib( 3711): linux_qmi_qmux_if_client_get_client_id [3711]: qmux_client_id=13
E/Diag_Lib( 3711): qmi_client [3711] 13: qmux_client ID is initialized
E/Diag_Lib( 3711): qmi_client [3711] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3711): qmi_client [3711] 13: sending 880 bytes on fd = 8
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3711): Sending signal ...... to read cmd data 
E/Diag_Lib( 3711): qmi error code.........:0
E/Diag_Lib( 3711): qmi sys error code.........:0
E/Diag_Lib( 3711): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3711): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3711): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3711): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3711): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3711): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3711): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3711): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3711): qmi_init:  Created client handle b8137788
,E/Diag_Lib( 3711): qmi_client [3711] 13: sending 880 bytes on fd = 8
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3711): Sending signal ...... to read cmd data 
E/Diag_Lib( 3711): qmi error code.........:0
,E/Diag_Lib( 3711): qmi sys error code.........:0
E/Diag_Lib( 3711): Setting the api flag to : 1
,E/Diag_Lib( 3711): qmi_client [3711] 13: sending 54 bytes on fd = 8
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 3714): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3714): rfkill: Cannot open RFKILL control device
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,E/Diag_Lib( 3714): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3714): Setting internal use port to rmnet0
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,E/wpa_supplicant( 3714): baseband property is set to [msm]
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/rmt_storage(  407): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb73fc1d0
I/rmt_storage(  407): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  407): wakelock acquired: 1, error no: 42
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220558280)
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3711):  API Flag .............. 1 
,E/Diag_Lib( 3711):  Message ID ............... 92 
,E/wpa_supplicant( 3714):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3714): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3714): card_info[i].card_state: 0x2
E/wpa_supplicant( 3714): card_info[i].error_code: 0x3
E/wpa_supplicant( 3714): SIM/USIM not ready
,E/wpa_supplicant( 3714): Error while reading SIM card status
,E/wpa_supplicant( 3714): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3714): card_info[i].card_state: 0x2
E/wpa_supplicant( 3714): card_info[i].error_code: 0x3
E/wpa_supplicant( 3714): SIM/USIM not ready
,I/wpa_supplicant( 3714): eap_proxy: Card not ready
,E/Diag_Lib( 3711): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3711): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3711): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3711): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3711): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3711): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3711): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3711): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3711): qmi_client [3711] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3711): Sending signal ...... to read cmd data 
E/Diag_Lib( 3711): qmi error code.........:0
E/Diag_Lib( 3711): qmi sys error code.........:0
E/Diag_Lib( 3711): qmi_release: Released client handle ff
E/Diag_Lib( 3711): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3711): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3711): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3711): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3711): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3711): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3711): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3711): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3711): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3711): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3711): qmi_client [3711] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3711): qmi_client [3711] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3711): Sending signal ...... to read cmd data 
E/Diag_Lib( 3711): qmi error code.........:0
E/Diag_Lib( 3711): qmi sys error code.........:0
E/Diag_Lib( 3711): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3711] 13
E/Diag_Lib( 3711): qmi_client [3711] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3711): qmi_client [3711] 13: failed to locate client data
E/Diag_Lib( 3711): qmi_client [3711] 13: calling release of fd=8
,E/Diag_Lib( 3711): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  407): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220558280) wakelock released: 1, error no: 0
I/rmt_storage(  407): 
,I/rmt_storage(  407): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb73fc1d0
,I/wpa_supplicant( 3714): Long line in configuration file truncated
,I/wpa_supplicant( 3714): rfkill: Cannot open RFKILL control device
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,E/wpa_supplicant( 3714): COUNTRY Code Recived
,E/wpa_supplicant( 3714): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3714): baseband property is set to [msm]
,E/wpa_supplicant( 3714):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3714): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3714): card_info[i].card_state: 0x2
E/wpa_supplicant( 3714): card_info[i].error_code: 0x3
E/wpa_supplicant( 3714): SIM/USIM not ready
,E/wpa_supplicant( 3714): Error while reading SIM card status
E/wpa_supplicant( 3714): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3714): card_info[i].card_state: 0x2
E/wpa_supplicant( 3714): card_info[i].error_code: 0x3
E/wpa_supplicant( 3714): SIM/USIM not ready
,I/wpa_supplicant( 3714): eap_proxy: Card not ready
I/qcom-bluetooth( 3718): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
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
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
,D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,I/qcom-bluetooth( 3720): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1255): Active network info is not available
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3714): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
,D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =IDLE and new state=DISCONNECTED
E/wpa_supplicant( 3714): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3714): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
,I/bt_hwcfg( 3634): bluetooth satus is on
I/GKI_LINUX( 3634): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
D/bt_userial_mct( 3634): userial_open(port:0)
,I/bt-btu  ( 3634): btu_task pending for preload complete event
I/bt_userial_vendor( 3634): Done intiailizing UART
I/bt_userial_vendor( 3634): Done intiailizing UART
I/bt_userial_mct( 3634): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
,I/bt_vendor( 3634): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 3634): Entering userial_read_thread()
I/bt-btu  ( 3634): btu_task received preload complete event
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
I/        ( 3634): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3634): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3634): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3634): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3634): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3634): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3634): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3634): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3634): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3634): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3634): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3634): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3634): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3634): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3634): BTE_InitTraceLevels -- TRC_BTIF
D/CommandListener(  273): Setting iface cfg
D/CommandListener(  273): Trying to bring up p2p0
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
,D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
E/wpa_supplicant( 3714): COUNTRY Code Recived
E/wpa_supplicant( 3714): COUNTRY Code Recived
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set frequency band 2
,D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
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
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): MCC mode enabled 0
D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-18ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-18ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
E/bt-btm  ( 3634): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f0ca049 
,E/bt-btm  ( 3634): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f0ca049 
D/WifiP2pService( 1019): InactiveState{ when=-19ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-19ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3714): COUNTRY Code Recived
,E/wpa_supplicant( 3714): COUNTRY Code Recived
D/WifiP2pService( 1019): InactiveState{ when=-11ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-11ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/bt-btif ( 3634): Calling BTA_HhEnable
E/bt-btif ( 3634): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3634): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothManagerService( 1019): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService( 1019): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3634): Name is: XT1039
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3634): Scan Mode:21
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3634): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:8 len:6
D/BluetoothAdapterProperties( 3634): Adding bonded device:B4:CE:F6:AB:A4:6A
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:3 len:48
E/BluetoothRemoteDevices( 3634): devicePropertyChangedCallback: bdDevice: B4:CE:F6:AB:A4:6A, value is empty for type: 10
I/bte_conf( 3634): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3634): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 3634): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 3634): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/bt_mct  ( 3634): hci lib postload completed
D/BluetoothAdapterState( 3634): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3634): ScanMode =  21
D/BluetoothAdapterProperties( 3634): State =  11
D/BluetoothAdapterProperties( 3634): Setting state to 12
I/BluetoothAdapterState( 3634): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3634): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 3634): Entering On State
D/BluetoothManagerService( 1019): Message: 60
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan( 1019): onBluetoothStateChange on: true
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
D/BluetoothPanServiceJni( 3634): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3634): Discoverable Timeout:120
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
D/BluetoothManagerService( 1019): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3634): onReceive
D/BluetoothMapService( 3634): STATE_ON
D/BluetoothMapService( 3634): Map Service startRfcommSocketListener
D/BluetoothManagerService( 1019): Message: 40
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3634): Map Service initSocket
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregro,undUser=0
W/BluetoothAdapter( 3634): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3634): SOCK FLAG = 1 ***********************
D/BluetoothMapService( 3634): Accepting socket connection...
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3634): Scan Mode:21
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
I/qcom-bt-wlan-coex( 3734): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c79bb8:true
D/BluetoothPbapService( 3634): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothPbapService( 3634): Handler(): got msg=1
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
W/BluetoothAdapter( 3634): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3634): SOCK FLAG = 1 ***********************
D/LocalBluetoothProfileManager( 3660): Adding local A2DP profile
D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3660): Adding local HEADSET profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3660): Adding local MAP profile
D/BluetoothMap( 3660): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3660): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3660): finishStartingService: stopping service
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothA2dp( 3660): Proxy object connected
,D/A2dpProfile( 3660): Bluetooth service connected
,D/BluetoothHeadset( 3660): Proxy object connected
,D/HeadsetProfile( 3660): Bluetooth service connected
,D/BluetoothInputDevice( 3660): Proxy object connected
,D/HidProfile( 3660): Bluetooth service connected
,D/BluetoothPan( 3660): BluetoothPAN Proxy object connected
D/PanProfile( 3660): Bluetooth service connected
D/BluetoothMap( 3660): Proxy object connected
D/MapProfile( 3660): Bluetooth service connected
,D/BluetoothMap( 3660): getConnectedDevices()
,D/BluetoothPbap( 3660): Proxy object connected
,D/PbapServerProfile( 3660): Bluetooth service connected
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
V/BluetoothFtpService( 3634): Ftp Service onCreate
I/BluetoothFtpService( 3634): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3634): Starting FTP service
V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpService( 3634): Handler(): got msg=1
V/BluetoothFtpService( 3634): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3634): Ftp Service initSocket
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3634): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3634): SOCK FLAG = 0 ***********************
I/BtOppRfcommListener( 3634): Accept thread started.
,W/BluetoothAdapter( 3634): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3634): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3634): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3634): Run Accept thread
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/dalvikvm( 1019): GC_EXPLICIT freed 22540K, 65% free 17834K/50020K, paused 5ms+10ms, total 149ms
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,I/MDMCTBK (  275): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  275): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): wifi_connect_to_supplicant, current pid is = 275
D/MDMCTBK (  275): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  275): wifi_close_sockets: Exit
,E/MDMCTBK (  275): Attach monitor thread
I/MDMCTBK (  275): createWifiMonitorThread: Started the wifi monitor thread -1195148464
,D/MDMCTBK (  275): wifi_wait_on_socket: Enter monitor thread
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
,I/wpa_supplicant( 3714): wlan0: Trying to associate with SSID 'NG700'
I/wpa_supplicant( 3713): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 3713): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
E/wpa_supplicant( 3714): DSDS: eapol_sm_notify_config config->sim_slot = 0
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  275): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 64:7c:34:b0:03:6e
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 64:7c:34:b0:03:6e
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  275): Event received = Trying to associate with
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 3714): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3714): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 312 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 88 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
I/wpa_supplicant( 3714): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3714): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
I/wpa_supplicant( 3714): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
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
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1194997248
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
,D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-28ms what=147462 obj=android.net.wifi.StateChangeResult@4218ee08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-18ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@424c1b28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428366e8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428366e8 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3584): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): my name is : motorola-XT1039_PT6879
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): attempting to connect to test coordinator
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): check test folder
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): found test : ./testFindPeers.js
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): found test : ./testReConnect.js
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): found test : ./testSendData.js
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Test app app.js loaded
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 6
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 5 64
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/WifiP2pService( 1019): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@430e03b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@430e03b0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@430e03b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 20
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-6ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
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
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,V/ConnectivityService( 1019): WiFi NOT Tethered!
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42025e70
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectedState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1282): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=0
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42025e70
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1282): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=0
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Coordinator is now connected to the server!
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,D/        ( 1019): Setting time of day to sec=1448880853
,W/        ( 1019): Unable to set rtc to 1448880853: Invalid argument
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,D/PollingManager( 1533): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3828 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
D/PollingManager( 1533): now: 334890 ,futureTime: 18185425
,D/PollingManager( 1533): Polling alarm set to expire at: 18185425 Current Time: 334890
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
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
,E/ActivityThread( 1533): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1533): registerApp(): CCE
I/CCE     ( 1533): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1533): Registering with Alarm Manager to restart CCE
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 1019):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,D/PollingManager( 1533): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/PollingManager( 1533): now: 334946 ,futureTime: 18185425
,D/PollingManager( 1533): Polling alarm set to expire at: 18185425 Current Time: 334946
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,E/ActivityThread( 1533): Failed to find provider info for com.motorola.blur.setupprovider
D/MMApiWebService( 1533): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1533): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1533): isRequestAllowed(): already have outstanding request ... ignoring request
D/CCE     ( 1533): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1533): isRequestAllowed(): already have outstanding request ... ignoring request
D/MMApiWebService( 1533): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1533): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/OtaApp  ( 1533): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/MMApiWebService( 1533): generating token using payload instead of using session token
D/OtaApp  ( 1533): [debug] > CusSM.onRadioUp
D/OtaApp  ( 1533): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1533): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1533): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 1533): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1533): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager( 1019): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3863 uid=10056 gids={50056, 3003, 1028, 1015}
D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1533): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/dalvikvm( 3828): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f3b290, skipping init
I/openssl ( 3828): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3828): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Killing 3431:com.android.defcontainer/u0a13 (adj 15): empty #9
I/dalvikvm( 1381): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1381): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1381): VFY: replacing opcode 0x6e at 0x0033
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/VacuumService( 1355): Vacuum at: now=1448880853802 tag=VacuumService
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3892 uid=10030 gids={50030, 3003, 1028, 1015}
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,I/jxcore-log( 3584): BLE advertisement not supported: Not supported
I/jxcore-log( 3584): 
,I/dalvikvm( 1203): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1203): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1203): VFY: replacing opcode 0x6e at 0x0033
,E/Auth.Api.Credentials( 1381): [CredentialSyncAdapter] Unknown sync event.
,D/DelayedSyncController( 3863): Delaying sync.
,D/GpsLocationProvider( 1019): NTP server returned: 1448880850519 (Mon Nov 30 11:54:10 CET 2015) reference: 331873 certainty: 18 system time offset: -3362
,V/MmsConfig( 3892): mnc/mcc: 
V/MmsConfig( 3892): tag: bool value: enabledMMS - true
,V/MmsConfig( 3892): tag: int value: maxMessageSize - 307200
V/MmsConfig( 3892): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3892): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3892): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3892): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 3892): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3892): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 3892): tag: int value: recipientLimit - 20
V/MmsConfig( 3892): tag: bool value: enableMultipartSMS - true
,V/MmsConfig( 3892): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3892): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3892): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3892): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 3892): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3892): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 3892): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3892): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,E/LocSvc_ApiV02( 1019): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3919 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 3071:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 3460:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1238): GC_EXPLICIT freed 1528K, 45% free 9517K/17224K, paused 3ms+21ms, total 67ms
,D/MobileConnectivityChangeReceiver( 3919): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3919): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3919): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3919): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3933 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3088:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1448877723144 min interval config: 0 actual interval: 3130880
,I/CheckinService( 1381): Checking schedule, now: 1448880854037 next: 1448877753122
,I/CheckinService( 1381): active receiver: enabled
,I/CheckinService( 1381): Preparing to send checkin request
,I/EventLogService( 1381): Accumulating logs since 1448879792368
,D/DelayedSyncController( 3863): Delaying sync.
,D/dalvikvm( 1355): GC_EXPLICIT freed 1230K, 39% free 10570K/17224K, paused 2ms+7ms, total 39ms
,V/WebViewChromiumFactoryProvider( 3933): Binding Chromium to main looper Looper (main, tid 1) {41f38268}
,I/LibraryLoader( 3933): Expected native library version number "",actual native library version number ""
,I/chromium( 3933): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3933): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3933): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3933): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3933): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3933): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3933): Local Branch: 
I/Adreno-EGL( 3933): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3933): Local Patches: NONE
I/Adreno-EGL( 3933): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/dalvikvm( 1381): GC_CONCURRENT freed 1707K, 33% free 11673K/17224K, paused 4ms+8ms, total 51ms
,W/chromium( 3933): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/CheckinRequestBuilder( 1381): Checkin reason type: 8 attempt count: 1
D/WifiService( 1019): New client listening to asynchronous messages
E/ActivityThread( 1381): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1019): GC_EXPLICIT freed 1777K, 65% free 17816K/50020K, paused 5ms+9ms, total 92ms
,W/GAV2    ( 3933): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3933): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3974 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 3974): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 3974): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 3974): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 3974): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3974): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 3974): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3974): install
,I/MultiDex( 3974): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 3974): loading existing secondary dex files
,I/MultiDex( 3974): load found 3 secondary dex files
,I/MultiDex( 3974): install done
,I/NSApplication( 3933): Starting up...
,I/ImageResourceManager( 3106): ImageResourceManager: uninitalized
,I/iu.Environment( 3106): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3106): SYNC; picasa accounts
I/ActivityManager( 1019): Killing 3486:com.google.android.apps.docs/u0a59 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.UploadsManager( 3106): num queued entries: 0
,I/iu.UploadsManager( 3106): num updated entries: 0
,I/iu.SyncManager( 3106): NEXT; no task
,D/dalvikvm( 3974): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3974): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3974): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 3974): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3974): VFY: unable to resolve instance field 46
,D/dalvikvm( 3974): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3974): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3974): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3974): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3974): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3974): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 3974): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f3de38
,D/dalvikvm( 3974): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f3de38
,D/dalvikvm( 3974): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f3de38, skipping init
,D/dalvikvm( 3974): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f3de38
D/dalvikvm( 3974): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f3de38
,V/JNIHelp ( 3974): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/iu.SyncManager( 1381): SYNC; picasa accounts
,D/NetworkLogImpl( 1381): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1381): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1381): num queued entries: 0
,I/iu.UploadsManager( 1381): num updated entries: 0
,I/iu.SyncManager( 1381): NEXT; no task
,D/dalvikvm( 3974): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f3de38
,D/dalvikvm( 3974): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41f3de38
D/dalvikvm( 3974): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f3de38
,D/dalvikvm( 3974): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f3de38
,I/openssl ( 3828): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3828): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 3919): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3919): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 3106): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/DEBUG   ( 1533): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1533): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1533): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=1
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4011 uid=10007 gids={50007, 3003}
,D/MMApiProvisionService( 1533): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"169022","deviceId":"1135300315450105856"}
,I/ProviderInstaller( 3974): Installed default security provider GmsCore_OpenSSL
D/MMApiProvisionService( 1533): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1533): doRequest(): /v1/dp/devices.json resp length: 138
,D/MMApiProvisionService( 1533): MMApiProvisionService.handleResponse (update_device) : true (None)
,D/MMApiProvisionService( 1533): handleResponse(): Session Expiration alarm set to expire at: Wed Dec 02 10:51:16 CET 2015
,D/MMApiProvisionService( 1533): _setMMApiCredInfo: storing credential info 
,D/ExtensionsFactory( 4011): No custom extensions.
,E/MMApiProvisionService( 1533): handleResponse(): no settings sent by the server:
,I/dalvikvm( 3974): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
,W/dalvikvm( 3974): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3974): VFY: replacing opcode 0x6e at 0x000d
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=4030 uid=10015 gids={50015, 1028}
,D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
I/ActivityManager( 1019): Killing 3140:com.android.vending/u0a38 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4041 uid=10008 gids={50008, 3003, 1028, 1015}
I/dalvikvm( 3974): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 3974): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 3974): VFY: replacing opcode 0x6e at 0x0220
D/MMApiWebService( 1533): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,I/ActivityManager( 1019): Killing 3660:com.android.settings/1000 (adj 15): empty #9
,D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 23ms
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/GCM     ( 1355): GCM config loaded
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
,I/dalvikvm( 3974): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 3974): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 3974): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 3974): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
,D/dalvikvm( 3974): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 3974): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 3974): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3974): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 3974): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 3974): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 3974): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
D/WifiService( 1019): Client connection lost with reason: 4
,D/MMApiWSBase( 1533): doRequest(): v1/ns/list/messages resp length: 1465
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,D/CCE     ( 1533): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1533): AppWSProxy - sendAIDLWSResponse() sending reponse
,V/AlarmClock( 4030): AlarmInitReceiver android.intent.action.TIME_SET
,D/WVCdm   (  281): Instantiating CDM.
I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/Checkin ( 1533): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1533): handleGetNotificationsResponse(): got 0; more=false
,I/GCM     ( 1355): Ack for not saved message 20
,I/AlarmClock( 4030): Displaying next alarm time: ''
,I/CalendarProvider2( 4041): Created com.android.providers.calendar.CalendarAlarmManager@41f54f90(com.android.providers.calendar.CalendarProvider2@41f4cb48)
,V/AlarmClock( 4030): AlarmInitReceiver finished
D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  281): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  281): App is not loaded in QSEE
E/QSEECOMAPI: (  281): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  281): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  281): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  281): App is not loaded in QSEE
E/QSEECOMAPI: (  281): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  281): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  281): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  281): App is not loaded in QSEE
I/ActivityManager( 1019): Killing 3828:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/QSEECOMAPI: (  281): Loaded image: APP id = 3
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5197000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5197000
,D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/UdcCache:FPQuery( 1381): Bootstrapping UDC settings cache for all accounts
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=210609396
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4066 uid=10098 gids={50098}
,D/dalvikvm( 4066): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41f36aa8, skipping init
D/TimeService( 4066): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448880855133
D/        ( 4066): TimeServiceNative: User Time to be set is 1448880855133
D/QC-time-services( 4066): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4066): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4066): Lib:time_genoff_operation: pargs->ts_val = 1448880855133
D/QC-time-services( 4066): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  396): Daemon: Connection accepted:time_genoff
D/QC-time-services(  396): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448880855133
D/QC-time-services(  396): Daemon:genoff_opr: Base = 2, val = 1448880855133, operation = 0
D/QC-time-services(  396): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/30/115 10:48:23
D/QC-time-services(  396): Daemon:Value read from RTC seconds = 1448880503000
D/QC-time-services(  396): Daemon:new time 1448880855133 
D/QC-time-services(  396): Daemon: delta 352133 genoff 352133 
D/QC-time-services(  396): Daemon:genoff_persistent_update: Writing genoff = 352133 to memory
D/QC-time-services(  396): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  396): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  396): Updating the TOD offset
D/QC-time-services(  396): Daemon:genoff_persistent_update: Writing genoff = 352133 to memory
D/QC-time-services(  396): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  396): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  396): Daemon:Update to modem bit set
D/QC-time-services(  396): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  396): Daemon: Base = 2, Value being sent to MODEM = 18446743757745103749
,E/QC-time-services( 4066): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  396): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  396): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1448877723144 min interval config: 0 actual interval: 3132028
,D/dalvikvm( 3974): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f7ff8
,D/dalvikvm( 3974): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f7ff8
,D/dalvikvm( 3974): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f7ff8, skipping init
,D/DEBUG   ( 1533): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1533): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1533): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1533): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1533): [debug] > UpdateReceiver: Received True from doSanityCheck.
,I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1533
D/NativeLibraryUtils( 3974): Install completed successfully. count=13 extracted=0
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1533): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1533
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 3584): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler( 1019): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,142
D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{424c5c40 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,D/WearableService( 1203): callingUid 10022, callindPid: 1203
,E/MDM     ( 1203): [76] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1381): Restart initialization of location
,D/AuthorizationBluetoothService( 1355): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1282): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1282): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,V/GmsCoreStatsServiceLauncher( 1381): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/DEBUG   ( 1533): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1533): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
,I/SundryService( 1533): Received shoulder tap
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4088 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,D/WaitableIntentService( 1533): setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1355): location=null
,D/GetNotificationsWS( 1533): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
,D/GetNotificationsWS( 1533): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=2
,D/dalvikvm( 1533): GC_CONCURRENT freed 3039K, 38% free 10828K/17224K, paused 3ms+4ms, total 42ms
,D/MMApiWebService( 1533): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1533): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1533): publish the event [tag = MOT_CCE event name = LOG]
,D/GetConfigurationSnapshotOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1355): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1355): Using platform SSLCertificateSocketFactory
,I/Babel   ( 4088): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4088): MmsConfig.loadMmsSettings
I/Babel   ( 4088): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4088): MmsConfig.loadFromDatabase
,E/Babel   ( 4088): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4088): MmsConfig.loadFromResources
,E/Babel   ( 4088): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4088): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4088): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DEBUG   ( 1533): Received intent : com.motorola.ccc.notification.action.NOTIFY
,I/SundryService( 1533): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1533): setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
D/SundryService( 1533): onHandleIntent(): isWaitEnabled=true
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=1
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=2219714082
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 1355): GC_CONCURRENT freed 1631K, 37% free 10943K/17224K, paused 3ms+6ms, total 40ms
,I/CalendarProvider2( 4041): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4041): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4011): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4011): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/MMApiWSBase( 1533): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1533): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1533): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1533): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1533): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1533): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1533): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1533): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1533): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1533): unbindWebServices(): un-registering our AIDL callback...
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 3974): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,W/Uploader( 1355):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 4129): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 3974): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 3974): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 83ms
,I/Adreno-EGL( 3974): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3974): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3974): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3974): Local Branch: 
I/Adreno-EGL( 3974): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3974): Local Patches: NONE
I/Adreno-EGL( 3974): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3974): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3974): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3974): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3974): Local Branch: 
I/Adreno-EGL( 3974): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3974): Local Patches: NONE
I/Adreno-EGL( 3974): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Adreno-EGL( 3974): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3974): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3974): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3974): Local Branch: 
I/Adreno-EGL( 3974): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3974): Local Patches: NONE
I/Adreno-EGL( 3974): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 3974): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3974): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3974): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3974): Local Branch: 
I/Adreno-EGL( 3974): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3974): Local Patches: NONE
I/Adreno-EGL( 3974): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 3974): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/dalvikvm( 1019): GC_EXPLICIT freed 836K, 65% free 17769K/50020K, paused 4ms+10ms, total 87ms
,I/CheckinRequestBuilder( 1381): Classify the device as Phone.
,I/CheckinTask( 1381): Sending checkin request (11648 bytes)
,I/Babel   ( 4088): Account registration complete:Redacted-21
,I/CheckinRequestBuilder( 1381): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1381): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1381): Classify the device as Phone.
,I/CheckinTask( 1381): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1381): Checking schedule, now: 1448880857492 next: 1449473927486
,I/CheckinService( 1381): active receiver: disabled
,D/CheckinService( 1381): Recording last checkin time for package unspecified as 1448880857506
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 3933): Thread[GAThread,5,main]: No campaign data found.
,I/GlobalDismissManager( 4011): no sender configured
,D/AlertService( 4011): Beginning updateAlertNotification
,D/AlertService( 4011): No fired or scheduled alerts
,D/AlertService( 4011): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4011): No events found starting within 1 week.
I/ActivityManager( 1019): Killing 3892:com.android.mms/u0a30 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 3919:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 3863:com.android.chrome/u0a56 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
W/ActivityThread( 1019): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1019):   Scheme: "sms"
I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4184 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/Launcher( 1294): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Launcher( 1294): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/Launcher( 1294): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1294): Deferring update until onResume
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
,I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/ActivityManager( 1019): Killing 3933:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1019):   Scheme: "smsto"
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1019):   Scheme: "mms"
I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4211 uid=10033 gids={50033, 3003, 1028, 1015}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,V/GmsNetworkLocationProvi( 1203): DISABLE
,I/GCoreNlp( 1203): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/InternalIcingCorporaPro( 2193): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4231 uid=10038 gids={50038, 3003, 1028, 1015}
D/PackageBroadcastService( 1381): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/dalvikvm( 3106): GC_CONCURRENT freed 641K, 5% free 16466K/17224K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 3106): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/PeopleContactsSync( 1381): CP2 sync disabled
,I/dalvikvm-heap( 3106): Grow heap (frag case) to 19.848MB for 1821008-byte allocation
,I/ActivityManager( 1019): Killing 4041:com.android.providers.calendar/u0a8 (adj 15): empty #9
,I/InternalIcingCorporaPro( 2193): UpdateCorporaTask done [took 47 ms] updated apps [took 46 ms] 
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3106): GC_FOR_ALLOC freed 7K, 5% free 18237K/19004K, paused 23ms, total 25ms
,D/dalvikvm( 1381): GC_CONCURRENT freed 1963K, 33% free 11645K/17224K, paused 4ms+6ms, total 50ms
,I/ContactLocale( 4184): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4231): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4231): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4231): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4231): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4231): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 4231): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4231): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4231): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4231): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4231): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4231): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4231): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4231): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4231): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4231): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4231): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4231): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4231): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4266 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm( 1019): GC_CONCURRENT freed 1968K, 65% free 17885K/50020K, paused 3ms+10ms, total 86ms
,I/dalvikvm( 4231): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4231): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x0019
,D/Finsky  ( 4231): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4231): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4231): Skipping gmscore version check
,I/dalvikvm( 4231): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 4231): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4231): VFY: replacing opcode 0x6e at 0x0017
,I/InternalIcingCorporaPro( 2193): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager( 1019): Killing 4066:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/PackageBroadcastService( 1381): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1381): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1381): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 4266): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f3d0e8, skipping init
I/openssl ( 4266): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4266): Crypto mode 0 already enabled
,D/Finsky  ( 4231): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4231): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1019): Killing 4030:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2193): UpdateCorporaTask done [took 261 ms] updated apps [took 261 ms] 
,V/AlarmManager( 1019): sending alarm Alarm{427f6328 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{427f51f8 type 3 android}
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
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3584): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): DBG, CoordinatorConnector command called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"80:01:84:8A:B3
,I/jxcore-log( 3584): Start now : testSendData.js
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): check server
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): serverPort is 46601
I/jxcore-log( 3584): 
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): initialize: F4:F1:E1:5C:3B:E2 motorola-XT1039_PT6879
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3584): initialize: My bluetooth address is F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): initialize: Bluetooth and Wi-Fi OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): setState: INITIALIZED
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): verifyIdentityString: Identity string created: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6879"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3634): SOCK FLAG = 0 ***********************
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): start: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): setState: RUNNING
,I/jxcore-log( 3584): StartBroadcasting started ok
I/jxcore-log( 3584): 
I/jxcore-log( 3584): do fake peer & start
I/jxcore-log( 3584): 
I/jxcore-log( 3584): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:55:56.761Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T10:55:56.762Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T10:55:56.762Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: null 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to null in address 34:FC:EF:11:AE:67
,I/jxcore-log( 3584): 2015-11-30T10:55:56.771Z SendDataTCPServer.js: TCP/IP server is bound to port: 46601
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
I/BluetoothBondStateMachine( 3634): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/ActivityManager( 1019): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=4312 uid=10011 gids={50011, 3003, 3002, 3001}
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42272068:true
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4276add8:true
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=4324 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1019): Killing 4011:com.android.calendar/u0a7 (adj 15): empty #9
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 3634): Ftp Service onStartCommand
V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/ActivityManager( 1019): Killing 3974:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,V/AlarmManager( 1019): sending alarm Alarm{428d3a88 type 3 android}
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, LGE-Nexus 5_PT8322
,I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3584): mHTTPPort  set to : 45534
I/BtConnectorHelper( 3584): Request socket is using : 45534
,I/BtToRequestSocket( 3584): Now accepting connections
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb,
E/bt-btif ( 3634): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: 34:FC:EF:11:AE:67
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass1f00
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :45534
,I/jxcore-log( 3584): 2015-11-30T10:56:00.805Z SendDataConnector.js: CLIENT connected to 45534, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:00.807Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 45534
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T10:56:00.827Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,I/jxcore-log( 3584): 2015-11-30T10:56:01.726Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:01.919Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:01.994Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:02.100Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:02.252Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:02.405Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:02.554Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:02.795Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:02.982Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3584): 
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
,I/jxcore-log( 3584): 2015-11-30T10:56:52.984Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:52.986Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:52.995Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:52.996Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:52.998Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: LGE-Nexus 5_PT8322
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 3584): 2015-11-30T10:56:57.998Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:56:57.999Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,V/AlarmManager( 1019): sending alarm Alarm{42765f60 type 3 android}
,I/jxcore-log( 3584): 2015-11-30T10:57:03.004Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:57:03.005Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:57:03.007Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:57:03.008Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: Nexus 5 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[129]}
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, LGE-Nexus 5_PT8322
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 294)
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 50005
,I/BtConnectorHelper( 3584): Request socket is using : 50005
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :50005
,I/jxcore-log( 3584): 2015-11-30T10:57:05.155Z SendDataConnector.js: CLIENT connected to 50005, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:57:05.156Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 50005
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T10:57:05.176Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 3
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
,I/jxcore-log( 3584): 2015-11-30T10:57:55.253Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:57:55.254Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:57:55.256Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:57:55.258Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:57:55.260Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: LGE-Nexus 5_PT8322
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,V/AlarmManager( 1019): sending alarm Alarm{420a0260 type 3 android}
,I/jxcore-log( 3584): 2015-11-30T10:58:00.260Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:00.261Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T10:58:05.266Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:05.267Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:05.268Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:05.269Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: Nexus 5 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[130]}
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, LGE-Nexus 5_PT8322
,I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 299)
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 44499
,I/BtConnectorHelper( 3584): Request socket is using : 44499
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :44499
,I/jxcore-log( 3584): 2015-11-30T10:58:07.356Z SendDataConnector.js: CLIENT connected to 44499, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:07.358Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 44499
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T10:58:07.371Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
,I/jxcore-log( 3584): 2015-11-30T10:58:57.431Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:57.431Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:57.435Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:57.436Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:58:57.438Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: LGE-Nexus 5_PT8322
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out,
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,V/AlarmManager( 1019): sending alarm Alarm{4283be28 type 3 android}
,I/jxcore-log( 3584): 2015-11-30T10:59:02.437Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:02.438Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
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
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T10:59:07.444Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:07.444Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:07.446Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:07.448Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: Nexus 5 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[131]}
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 304)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, LGE-Nexus 5_PT8322
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3584): mHTTPPort  set to : 46518
I/BtConnectorHelper( 3584): Request socket is using : 46518
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :46518
,I/jxcore-log( 3584): 2015-11-30T10:59:09.920Z SendDataConnector.js: CLIENT connected to 46518, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:09.921Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 46518
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T10:59:09.936Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1355): GC_CONCURRENT freed 2005K, 37% free 10914K/17224K, paused 22ms+8ms, total 71ms
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 83 bytes successfully (thread ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3739 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 308
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3739 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3739 7C:F9:0E:51:18:22]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, samsung-SM-A500FU_PT3739
,I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BTConnectedThread
,I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: 7C:F9:0E:51:18:22
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass5a020c
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,I/jxcore-log( 3584): 2015-11-30T10:59:34.305Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22936c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T10:59:34.959Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:34.968Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:34.972Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:34.977Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:34.980Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:34.983Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.014Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.017Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.020Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.056Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.059Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.094Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.098Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.105Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.107Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.144Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.149Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.152Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.185Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.245Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.253Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.285Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T10:59:35.296Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3584): 
,W/bt-btif ( 3634): invalid rfc slot id: 5
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT3739
I/BtToSocketBase( 3584): Stop ReceivingThread
,I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x4c
,I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT3739
,I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T10:59:35.358Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229528 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4257c0b8 type 3 android}
,I/jxcore-log( 3584): 2015-11-30T11:00:00.024Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:00:00.025Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:00:00.026Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:00:00.026Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:00:00.027Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: LGE-Nexus 5_PT8322
I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
I/BtToSocketBase( 3584): Close local in
I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,V/AlarmManager( 1019): sending alarm Alarm{427efba8 type 1 com.android.deskclock}
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4455 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 4266:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22936c rs_disc_pending=0
W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
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
,I/jxcore-log( 3584): 2015-11-30T11:00:05.031Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:00:05.043Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:00:10.046Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:00:10.046Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:00:10.048Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:00:10.049Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: Nexus 5 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[132]}
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8322 34:FC:EF:11:AE:67]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, LGE-Nexus 5_PT8322
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 313)
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 55475
I/BtConnectorHelper( 3584): Request socket is using : 55475
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :55475
,I/jxcore-log( 3584): 2015-11-30T11:00:11.641Z SendDataConnector.js: CLIENT connected to 55475, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:00:11.643Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 55475
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:00:11.657Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
,V/AlarmManager( 1019): sending alarm Alarm{42254ef8 type 3 android}
,I/jxcore-log( 3584): 2015-11-30T11:01:01.720Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:01.721Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:01.725Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:01.755Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:01.755Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:01.756Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
I/BtConnectorHelper( 3584): Disconnect outgoing peer: 34:FC:EF:11:AE:67
I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,I/jxcore-log( 3584): 2015-11-30T11:01:01.761Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3584): 
I/jxcore-log( 3584): ---- round done--------
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): ---- gotta redo : 34:FC:EF:11:AE:67, try count now: 1
I/jxcore-log( 3584): 
I/jxcore-log( 3584): do fake peer & start
I/jxcore-log( 3584): 
I/jxcore-log( 3584): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:01.764Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:01:01.765Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:01.765Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: null 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to null in address 80:01:84:8A:B3:68
,I/jxcore-log( 3584): 2015-11-30T11:01:01.771Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:AE:67 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[133]}
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22936c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3634): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
,E/bt-btif ( 3634): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3634): invalid rfc slot id: 12
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): shutdown
,I/jxcore-log( 3584): 2015-11-30T11:01:07.858Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:07.859Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:07.860Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:01:12.863Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:12.884Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:17.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:17.890Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:17.891Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:17.893Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: null 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[135]}
,W/bt-sdp  ( 3634): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
,E/bt-btif ( 3634): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3634): invalid rfc slot id: 13
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): shutdown
,I/jxcore-log( 3584): 2015-11-30T11:01:23.085Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:23.087Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:23.088Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:28.091Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:28.092Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:33.096Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:33.097Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:33.098Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:33.100Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: null 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[136]}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
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
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 84 bytes successfully (thread ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT2983
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 46269
I/BtConnectorHelper( 3584): Request socket is using : 46269
,I/BtToRequestSocket( 3584): Now accepting connections
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 3 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 4 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 5 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 6 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 7 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 8 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 9 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 10 uuid:00001132-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 11 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3634): Index: 12 uuid:00006675-7475-7265-6469-616c62756d70
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: 80:01:84:8A:B3:68
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass1f00
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :46269
,I/jxcore-log( 3584): 2015-11-30T11:01:35.049Z SendDataConnector.js: CLIENT connected to 46269, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.050Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 46269
,I/BtToRequestSocket( 3584): Set local streams
I/jxcore-log( 3584): 2015-11-30T11:01:35.062Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,I/jxcore-log( 3584): 2015-11-30T11:01:35.658Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.703Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.736Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.741Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.780Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.828Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.881Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.931Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:01:35.979Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3584): 
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,V/AlarmManager( 1019): sending alarm Alarm{43684bd8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427ef048 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{427ee0c0 type 0 com.android.vending}
,D/Finsky  ( 4231): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 4231): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4231): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4231): VFY: replacing opcode 0x62 at 0x0038
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/dalvikvm( 1019): GC_EXPLICIT freed 871K, 65% free 17851K/50012K, paused 5ms+9ms, total 96ms
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 4231): Failed write_ctrl(u 67) res=-1 errno=22
,I/qtaguid ( 4231): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4231): untagSocket(67) failed with errno -22
,D/Finsky  ( 4231): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430000] >= Server Version [-1]
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 4231): Total arena pages for JIT: 11
,I/dalvikvm( 4231): Total arena pages for JIT: 12
I/dalvikvm( 4231): Total arena pages for JIT: 13
,I/dalvikvm( 4231): Total arena pages for JIT: 14
,I/qtaguid ( 4231): Failed write_ctrl(u 67) res=-1 errno=22
,I/qtaguid ( 4231): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4231): untagSocket(67) failed with errno -22
,D/dalvikvm( 4231): GC_FOR_ALLOC freed 4468K, 28% free 12484K/17224K, paused 29ms, total 29ms
,D/dalvikvm( 4231): GC_CONCURRENT freed 1726K, 26% free 12805K/17224K, paused 3ms+3ms, total 27ms
,D/dalvikvm( 4231): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 4231): GC_CONCURRENT freed 618K, 18% free 14235K/17224K, paused 1ms+2ms, total 34ms
,D/dalvikvm( 4231): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 4231): GC_CONCURRENT freed 1204K, 13% free 15078K/17224K, paused 2ms+4ms, total 41ms
,D/dalvikvm( 4231): WAIT_FOR_CONCURRENT_GC blocked 27ms
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/qtaguid ( 4231): Failed write_ctrl(u 67) res=-1 errno=22
,I/qtaguid ( 4231): Untagging socket 67 failed errno=-22
,W/NetworkManagementSocketTagger( 4231): untagSocket(67) failed with errno -22
,D/Volley  ( 4231): [327] BasicNetwork.performRequest: HTTP response for request=<[ ] https://android.clients.google.com/fdfe/bulkDetails?au=1 0xe8d195d1 NORMAL 4> [lifetime=7504], [size=47833], [rc=200], [retryCount=0]
,D/Finsky  ( 4231): [1] LibraryUtils.isAvailable: com.quickoffice.android available because owned, overriding [restriction=7].
,D/dalvikvm( 4231): GC_CONCURRENT freed 1982K, 13% free 15144K/17224K, paused 3ms+3ms, total 97ms
,D/dalvikvm( 4231): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/Finsky  ( 4231): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4231): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1019): sending alarm Alarm{42082e78 type 0 com.android.vending}
,D/DeviceConnectionService( 1203): client connected with version: 8296000
,D/Finsky  ( 4231): [349] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{43bb1068 type 0 com.android.vending}
,D/Finsky  ( 4231): [339] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4231): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3584): 2015-11-30T11:02:25.979Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:25.980Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:25.982Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:25.984Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:25.986Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: HTC-HTC Desire 820_PT2983
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/jxcore-log( 3584): 2015-11-30T11:02:30.986Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:30.986Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:02:35.991Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:35.991Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:35.993Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:35.995Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[137]}
,W/bt-sdp  ( 3634): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
,E/bt-btif ( 3634): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3634): invalid rfc slot id: 15
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): shutdown
,I/jxcore-log( 3584): 2015-11-30T11:02:41.185Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:41.187Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:41.189Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:46.191Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:46.192Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:51.197Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:51.197Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:51.199Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:51.201Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[138]}
,W/bt-sdp  ( 3634): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
,E/bt-btif ( 3634): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3634): invalid rfc slot id: 16
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Failed to connect to socket/initiate handshake
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT2983 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): shutdown
,I/jxcore-log( 3584): 2015-11-30T11:02:56.398Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:56.400Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:56.410Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:56.411Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:56.412Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): ---- round done--------
I/jxcore-log( 3584): 
I/jxcore-log( 3584): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): do fake peer & start
I/jxcore-log( 3584): 
I/jxcore-log( 3584): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:56.415Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:02:56.415Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:56.416Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: null E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[139]}
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
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 82 bytes successfully (thread ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4244 E0:DB:10:14:E2:C0]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, samsung-SM-N910C_PT4244
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 40549
I/BtConnectorHelper( 3584): Request socket is using : 40549
,I/BtToRequestSocket( 3584): Now accepting connections
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: E0:DB:10:14:E2:C0
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass1f00
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :40549
,I/jxcore-log( 3584): 2015-11-30T11:02:58.707Z SendDataConnector.js: CLIENT connected to 40549, error: null
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:02:58.708Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:58.711Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3584): 
I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 40549
,I/BtToRequestSocket( 3584): Set local streams
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,I/jxcore-log( 3584): 2015-11-30T11:02:59.294Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.297Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.345Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.392Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.396Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.447Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.508Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.513Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.564Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.592Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.593Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.613Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.614Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/BtConnectorHelper( 3584): Disconnect outgoing peer: E0:DB:10:14:E2:C0
,I/BtToSocketBase( 3584): Stop ReceivingThread
,I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in,
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,I/jxcore-log( 3584): 2015-11-30T11:02:59.628Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): ---- round done--------
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): do fake peer & start
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.631Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.632Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:02:59.633Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: null B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to null in address B0:C5:59:3F:75:69
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[140]}
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f2298a0 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,V/AlarmManager( 1019): sending alarm Alarm{42822078 type 3 android}
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f2298a0 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 332)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f2298a0 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 82 bytes successfully (thread ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 34950
,I/BtConnectorHelper( 3584): Request socket is using : 34950
,I/BtToRequestSocket( 3584): Now accepting connections
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: B0:C5:59:3F:75:69
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass1f00
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :34950
,I/jxcore-log( 3584): 2015-11-30T11:03:04.909Z SendDataConnector.js: CLIENT connected to 34950, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:04.911Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 34950
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:03:04.925Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,I/jxcore-log( 3584): 2015-11-30T11:03:06.817Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:06.982Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:07.137Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:03:07.264Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:07.390Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:07.445Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:07.514Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:07.582Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:07.635Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3584): 
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
,I/jxcore-log( 3584): 2015-11-30T11:03:57.635Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:57.635Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:57.640Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:57.641Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:03:57.645Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,V/AlarmManager( 1019): sending alarm Alarm{42deaad8 type 3 android}
,I/jxcore-log( 3584): 2015-11-30T11:04:02.645Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:02.646Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:04:07.650Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:07.651Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:07.652Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:07.654Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[141]}
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [b0:c5:59:3f:75:69]: 7, f, 2205
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 82 bytes successfully (thread ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 337)
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 45468
I/BtConnectorHelper( 3584): Request socket is using : 45468
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :45468
,I/jxcore-log( 3584): 2015-11-30T11:04:09.404Z SendDataConnector.js: CLIENT connected to 45468, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:09.406Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 45468
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:04:09.418Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229c18 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 341)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229c18 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229c18 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 80 bytes successfully (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 341
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BTConnectedThread
,I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/jxcore-log( 3584): 2015-11-30T11:04:33.088Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 8 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: 58:2A:F7:ED:96:BE
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass5a020c
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3584): 2015-11-30T11:04:33.887Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:33.895Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:33.901Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:33.906Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:33.920Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:33.956Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:33.971Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.007Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.035Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.040Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.062Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.076Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.115Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.129Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.140Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.190Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.225Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.250Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.254Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.264Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.295Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.368Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.377Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.405Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.424Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3584): 
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3584): 2015-11-30T11:04:34.456Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.485Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3584): 
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 3584): 2015-11-30T11:04:34.524Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.541Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.574Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.614Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.658Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.694Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.698Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:34.734Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3584): 
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/jxcore-log( 3584): 2015-11-30T11:04:59.481Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:59.481Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:59.485Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:59.486Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:04:59.488Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out,
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,V/AlarmManager( 1019): sending alarm Alarm{4208a2f0 type 3 android}
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T11:05:04.487Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:04.488Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/jxcore-log( 3584): 2015-11-30T11:05:09.492Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:09.493Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:09.494Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:09.496Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[142]}
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229c18 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3634): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 346)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 346)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 346)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 82 bytes successfully (thread ID: 346)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 346)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 56894
,I/BtConnectorHelper( 3584): Request socket is using : 56894
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :56894
,I/jxcore-log( 3584): 2015-11-30T11:05:14.476Z SendDataConnector.js: CLIENT connected to 56894, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:14.478Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 56894
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:05:14.506Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
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
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): invalid rfc slot id: 10
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7478
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:05:25.487Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229c18 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 350)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 80 bytes successfully (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 350
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT7478 58:2A:F7:ED:96:BE]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3584): Creating BTConnectedThread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 350)
I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/jxcore-log( 3584): 2015-11-30T11:05:47.319Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T11:05:47.716Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:47.720Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:47.728Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:47.736Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:05:47.741Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3584): 
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 8 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: 58:2A:F7:ED:96:BE
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass5a020c
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43bbdaf8 type 3 android}
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
,I/jxcore-log( 3584): 2015-11-30T11:06:04.566Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:04.566Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:06:04.567Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:06:04.567Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:04.567Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: samsung-SM-G900F_PT9998
I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
I/BtToSocketBase( 3584): Close local in
I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229c18 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:06:09.569Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:09.571Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/jxcore-log( 3584): 2015-11-30T11:06:14.577Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:14.578Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:14.579Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:14.581Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[143]}
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229c18 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 355)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 82 bytes successfully (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 60808
,I/BtConnectorHelper( 3584): Request socket is using : 60808
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :60808
,I/jxcore-log( 3584): 2015-11-30T11:06:18.150Z SendDataConnector.js: CLIENT connected to 60808, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:18.151Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 60808
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:06:18.164Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): invalid rfc slot id: 20
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7478
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7478
I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:06:38.475Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 83 bytes successfully (thread ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 359)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT5840 7C:F9:0E:37:96:AB]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, samsung-SM-A500FU_PT5840
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BTConnectedThread
I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,I/jxcore-log( 3584): 2015-11-30T11:06:54.574Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,D/BluetoothMetrics( 3634): btclass5a020c
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3584): 2015-11-30T11:06:55.325Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.331Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.337Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.345Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.380Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.388Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.399Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.436Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.440Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.450Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.460Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.498Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.538Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.575Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.586Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.624Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.627Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.629Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.665Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.690Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:06:55.725Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3584): 
,W/bt-btif ( 3634): invalid rfc slot id: 22
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT5840
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT5840
,I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:06:55.816Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229dd4 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x45
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
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/dalvikvm( 1019): GC_EXPLICIT freed 826K, 65% free 17906K/50012K, paused 5ms+10ms, total 98ms
,V/AlarmManager( 1019): sending alarm Alarm{430dfd68 type 3 android}
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3584): 2015-11-30T11:07:08.229Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:08.229Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:08.231Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:08.233Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:08.235Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T11:07:13.236Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:13.237Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED,
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:07:18.240Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:18.241Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:18.243Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:18.244Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[147]}
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 82 bytes successfully (thread ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3584): mHTTPPort  set to : 56518
I/BtConnectorHelper( 3584): Request socket is using : 56518
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :56518
,I/jxcore-log( 3584): 2015-11-30T11:07:20.484Z SendDataConnector.js: CLIENT connected to 56518, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:07:20.485Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 56518
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:07:20.511Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
,V/AlarmManager( 1019): sending alarm Alarm{445881c0 type 3 android}
,I/jxcore-log( 3584): 2015-11-30T11:08:10.568Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:10.569Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:10.571Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:10.593Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:10.594Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:10.596Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/BtConnectorHelper( 3584): Disconnect outgoing peer: B0:C5:59:3F:75:69
I/BtToSocketBase( 3584): Stop ReceivingThread
,I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,I/jxcore-log( 3584): 2015-11-30T11:08:10.608Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3584): 
I/jxcore-log( 3584): ---- round done--------
I/jxcore-log( 3584): 
I/jxcore-log( 3584): ---- gotta redo : B0:C5:59:3F:75:69, try count now: 1
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): do fake peer & start
I/jxcore-log( 3584): 
I/jxcore-log( 3584): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:08:10.610Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:08:10.611Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:10.611Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to null in address 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: null 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to null in address 50:2E:6C:AC:21:50
,I/jxcore-log( 3584): 2015-11-30T11:08:10.615Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[148]}
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 4312): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
I/wpa_supplicant( 3714): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/Tethering( 1019): InitialState.processMessage what=4
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): Network connection lost
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,V/ConnectivityService( 1019): WiFi NOT Tethered!
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3714): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3714): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 21
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 850618
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x611e8160 clazz=0x80a00001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1355): Read error: ssl=0x5d409248: I/O error during system call, Connection timed out
,V/NativeCrypto( 1355): SSL shutdown failed: ssl=0x5d409248: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
,D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/jxcore-log( 3584): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): The Coordinator has disconnected!
I/jxcore-log( 3584): 
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 3714): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/wpa_supplicant( 3714): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
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
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1282): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=0
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1282): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=0
D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3584): 
,D/WifiService( 1019): setWifiEnabled: false pid=3584, uid=10418
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1255): Active network info is not available
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange failed
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange failed
D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,W/wpa_supplicant( 3714): wlan0: Failed to initiate AP scan
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <4>Failed to initiate AP sc
,D/MDMCTBK (  275): Event received = Failed to initiate AP sc
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
,D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pDisablingState
D/WifiP2pService( 1019): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: X
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
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 3714): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3714): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  273): Clearing all IP addresses on wlan0
,D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=DISCONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): stopping supplicant
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): setWifiState: disabling
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
W/XTWiFiOS( 1255): Active network info is not available
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange failed
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange failed
,I/wpa_supplicant( 3714): eap_proxy Deinitialzed
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196614
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiService( 1019): setWifiEnabled: true pid=3584, uid=10418
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4924 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiController( 1019): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 384ms
D/WifiStateMachine( 1019): handleMessage: E msg.what=131145
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131146
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
I/jxcore-log( 3584): Wifi toggled for connection repairment
I/jxcore-log( 3584): 
W/XTWiFiOS( 1255): Active network info is not available
W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange failed
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onWifiStateChanged: State changed to 1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onWifiStateChanged: Bluetooth or Wi-Fi disabled, stopping Wi-Fi peer discovery...
E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange failed
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
I/wpa_supplicant( 3714): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  275): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  275):  Wpa Supplicant Exiting !!
D/MDMCTBK (  275): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  275): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  275): wifi_close_sockets: Exit
I/wpa_supplicant( 3714): CTRL_IFACE monitor[0]: 2 - No such file or directory
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1019): Supplicant connection lost
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42791e40:true
,D/LocalBluetoothProfileManager( 4924): Adding local A2DP profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 4924): Adding local HEADSET profile
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 4924): Adding local MAP profile
D/BluetoothMap( 4924): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 4924): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 4924): LocalBluetoothProfileManager construction complete
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothA2dp( 4924): Proxy object connected
,D/A2dpProfile( 4924): Bluetooth service connected
I/ActivityManager( 1019): Killing 4088:com.google.android.talk/u0a70 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothHeadset( 4924): Proxy object connected
D/HeadsetProfile( 4924): Bluetooth service connected
D/BluetoothInputDevice( 4924): Proxy object connected
D/HidProfile( 4924): Bluetooth service connected
D/BluetoothPan( 4924): BluetoothPAN Proxy object connected
D/PanProfile( 4924): Bluetooth service connected
D/BluetoothMap( 4924): Proxy object connected
D/MapProfile( 4924): Bluetooth service connected
D/BluetoothMap( 4924): getConnectedDevices()
D/BluetoothPbap( 4924): Proxy object connected
D/PbapServerProfile( 4924): Bluetooth service connected
,D/WifiStateMachine( 1019): setWifiState: disabled
,D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
W/XTWiFiOS( 1255): Active network info is not available
,W/Settings( 1203): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange failed
E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange failed
D/WifiService( 1019): New client listening to asynchronous messages
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiController( 1019): DEFERRED_TOGGLE handled
,D/WifiStateMachine( 1019): setting operational mode to 1
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/NetlinkEvent(  273): Unexpected netlink message. type=0x11
W/Netd    (  273): No subsystem found in netlink event
D/TCMD    (  437): NL - Read 444 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 17
D/TCMD    (  437): Listening for incoming client connection request
,I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  275): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/NetlinkEvent(  273): Unexpected netlink message. type=0x11
W/Netd    (  273): No subsystem found in netlink event
D/TCMD    (  437): NL - Read 444 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 17
D/TCMD    (  437): Listening for incoming client connection request
I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  275): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  275): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  275): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
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
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/MDMCTBK (  275): NetlinkHandler, wifiStateChanged 0
I/MDMCTBK (  275): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
,I/MDMCTBK (  275): checkDefaultInst, pid match
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
,D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131208
D/WifiStateMachine( 1019): processMsg: InitialState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131083
,D/WifiStateMachine( 1019): processMsg: InitialState
,I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is add
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
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
,E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/TCMD    (  437): NL - Read 1004 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
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
,E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  437): NL - Read 1004 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/QsoftapCmd(  273): Got softap fwreload command we are passing on
,D/SoftapController(  273): Softap fwReload - Ok
D/CommandListener(  273): Setting iface cfg
,D/CommandListener(  273): Trying to bring down wlan0
,E/WifiHW  ( 1019): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,E/WifiHW  ( 1019): ctrl_interface != /data/misc/wifi/sockets
,I/wpa_supplicant( 4970): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4970): rfkill: Cannot open RFKILL control device
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,E/Diag_Lib( 4970): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 4970): Setting internal use port to rmnet0
,E/wpa_supplicant( 4970): baseband property is set to [msm]
,E/wpa_supplicant( 4970):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4970): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4970): card_info[i].card_state: 0x2
E/wpa_supplicant( 4970): card_info[i].error_code: 0x3
E/wpa_supplicant( 4970): SIM/USIM not ready
,E/wpa_supplicant( 4970): Error while reading SIM card status
,E/wpa_supplicant( 4970): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4970): card_info[i].card_state: 0x2
E/wpa_supplicant( 4970): card_info[i].error_code: 0x3
E/wpa_supplicant( 4970): SIM/USIM not ready
,I/wpa_supplicant( 4970): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): setWifiState: enabling
D/WifiStateMachine( 1019): Supplicant start successful
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1255): Active network info is not available
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange failed
,E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange failed
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4970): Long line in configuration file truncated
,I/wpa_supplicant( 4970): rfkill: Cannot open RFKILL control device
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,E/wpa_supplicant( 4970): COUNTRY Code Recived
E/wpa_supplicant( 4970): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 4970): baseband property is set to [msm]
,E/wpa_supplicant( 4970):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4970): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4970): card_info[i].card_state: 0x2
E/wpa_supplicant( 4970): card_info[i].error_code: 0x3
E/wpa_supplicant( 4970): SIM/USIM not ready
,E/wpa_supplicant( 4970): Error while reading SIM card status
E/wpa_supplicant( 4970): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 4970): card_info[i].card_state: 0x2
E/wpa_supplicant( 4970): card_info[i].error_code: 0x3
E/wpa_supplicant( 4970): SIM/USIM not ready
,I/wpa_supplicant( 4970): eap_proxy: Card not ready
,D/WifiStateMachine( 1019): transitionTo: destState=SupplicantStartingState
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
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147457
D/WifiStateMachine( 1019): processMsg: SupplicantStartingState
D/WifiStateMachine( 1019): Supplicant connection established
,D/WifiStateMachine( 1019): setWifiState: enabled
,I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received,
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1255): Active network info is not available
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange failed
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange failed
,D/WifiConfigStore( 1019): Loading config and enabling all networks
,E/WifiConfigStore( 1019): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 4970): COUNTRY Code Recived -COUNTRY PL
,D/WifiStateMachine( 1019): transitionTo: destState=DriverStartedState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine( 1019): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
E/wpa_supplicant( 4970): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 4970): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine( 1019): Attempting to reconnect to wifi network ..
,D/WifiStateMachine( 1019): transitionTo: destState=DisconnectedState
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine( 1019): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine( 1019): invokeEnterMethods: ConnectModeState
,D/WifiStateMachine( 1019): invokeEnterMethods: DisconnectedState
,D/WifiP2pService( 1019): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
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
D/CommandListener(  273): Setting iface cfg
D/CommandListener(  273): Trying to bring up p2p0
E/wpa_supplicant( 4970): COUNTRY Code Recived
D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
,E/wpa_supplicant( 4970): COUNTRY Code Recived
D/WifiP2pService( 1019): P2pEnablingState
D/WifiP2pService( 1019): P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2p socket connection successful
D/WifiP2pService( 1019): P2pEnabledState
,D/WifiP2pService( 1019): sending p2p connection changed broadcast
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131162
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): set frequency band 2
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
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=143371
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
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): DeviceAddress: f4:f1:e1:5c:43:c8
D/WifiP2pService( 1019): MCC mode enabled 0
D/WifiP2pService( 1019): mP2pAutoConnectSupport = 0
D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
D/WifiP2pService( 1019): InactiveState
D/WifiP2pService( 1019): InactiveState{ when=-14ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-14ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): InactiveState{ when=-15ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-15ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 4970): COUNTRY Code Recived
,E/wpa_supplicant( 4970): COUNTRY Code Recived
D/WifiP2pService( 1019): InactiveState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-6ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1019): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1255): Active network info is not available
,D/PollingManager( 1533): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ActivityManager( 1019): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4976 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 22ms
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: null, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1255): Active network info is not available
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
I/MDMCTBK (  275): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  275): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
,I/MDMCTBK (  275): wifi_connect_to_supplicant, current pid is = 275
D/MDMCTBK (  275): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  275): wifi_close_sockets: Exit
E/MDMCTBK (  275): Attach monitor thread
,I/MDMCTBK (  275): createWifiMonitorThread: Started the wifi monitor thread -1195148464
,D/MDMCTBK (  275): wifi_wait_on_socket: Enter monitor thread
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 25ms
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,E/ActivityThread( 1533): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1533): connectivity_action: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PollingManager( 1533): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,E/ActivityThread( 1533): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1533): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 1533): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1533): [debug] > CusSM.onRadioDown
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,D/dalvikvm( 4976): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f42aa8, skipping init
I/openssl ( 4976): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4976): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5003 uid=10030 gids={50030, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4184:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/MmsConfig( 5003): mnc/mcc: 
,V/MmsConfig( 5003): tag: bool value: enabledMMS - true
V/MmsConfig( 5003): tag: int value: maxMessageSize - 307200
V/MmsConfig( 5003): tag: int value: maxImageHeight - 1944
V/MmsConfig( 5003): tag: int value: maxImageWidth - 2592
V/MmsConfig( 5003): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 5003): tag: int value: defaultMMSMessagesPerThread - 50
,V/MmsConfig( 5003): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 5003): tag: int value: maxMessageCountPerThread - 5000
V/MmsConfig( 5003): tag: int value: recipientLimit - 20
V/MmsConfig( 5003): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 5003): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 5003): tag: bool value: enableSlideDuration - true
V/MmsConfig( 5003): tag: int value: maxMessageTextSize - -1
,V/MmsConfig( 5003): tag: int value: maxSubjectLength - 80
V/MmsConfig( 5003): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 5003): tag: bool value: smsForce7BitEncoding - false
V/MmsConfig( 5003): tag: bool value: enableGroupMms - false
,E/MmsConfig( 5003): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager( 1019): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5022 uid=10041 gids={50041, 3003}
,I/ActivityManager( 1019): Killing 4211:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/MobileConnectivityChangeReceiver( 5022): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5022): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 5022): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5022): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5035 uid=10056 gids={50056, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3106:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5049 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 4455:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/WebViewChromiumFactoryProvider( 5049): Binding Chromium to main looper Looper (main, tid 1) {41f34ef8}
,I/LibraryLoader( 5049): Expected native library version number "",actual native library version number ""
,I/chromium( 5049): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5049): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 5049): BLUETOOTH permission is missing!
,I/Adreno-EGL( 5049): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5049): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5049): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5049): Local Branch: 
I/Adreno-EGL( 5049): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5049): Local Patches: NONE
I/Adreno-EGL( 5049): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 5049): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 5049): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5049): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,I/NSApplication( 5049): Starting up...
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5095 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
,I/ActivityManager( 1019): Killing 4231:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1019): GC_EXPLICIT freed 1157K, 65% free 17934K/50012K, paused 4ms+8ms, total 87ms
,I/ImageResourceManager( 5095): ImageResourceManager: uninitalized
,I/ActivityManager( 1019): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5114 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/iu.Environment( 5095): update battery state; isPlugged? true*
I/iu.Environment( 5095): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,I/iu.Environment( 5095): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
I/ActivityManager( 1019): Killing 4324:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019): Killing 4312:com.motorola.context/u0a11 (adj 15): empty #9
D/WifiP2pService( 1019): InactiveState{ when=-3ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=-3ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledStateupdate channel list
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.Environment( 1381): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1381): num queued entries: 0
,I/iu.UploadsManager( 1381): num updated entries: 0
,I/iu.SyncManager( 1381): NEXT; no task
,D/MobileConnectivityChangeReceiver( 5022): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5022): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 5095): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,D/DEBUG   ( 1533): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1533): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1533): bindWebServices(): registering our AIDL callback...
I/SundryService( 1533): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1533): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 1533): onServiceConnected()
,D/GetNotificationsWS( 1533): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 1533): unbindWebServices(): un-registering our AIDL callback...
,D/dalvikvm( 5095): GC_FOR_ALLOC freed 383K, 5% free 16402K/17224K, paused 14ms, total 14ms
,I/dalvikvm-heap( 5095): Grow heap (frag case) to 19.787MB for 1821008-byte allocation
,I/iu.UploadsManager( 5095): #reloadSettings(); account: null; pageID: none; IU: disabled; IS: disabled; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,I/iu.FingerprintManager( 5095): Start processing all media
,I/iu.FingerprintManager( 5095): Start processing media store URI: content://media/external/images/media
,D/dalvikvm( 5095): GC_FOR_ALLOC freed 21K, 5% free 18196K/19004K, paused 12ms, total 12ms
,I/iu.FingerprintManager( 5095): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 5095): End new media; added: 0, uploading: 0, time: 44 ms
,I/iu.FingerprintManager( 5095): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5095): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 5095): Finished generating fingerprints; 0.031 seconds
,I/iu.FingerprintManager( 5095):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/ContactLocale( 5114): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
I/wpa_supplicant( 4969): fatal error opening "/sys/power/wake_lock"
,I/wpa_supplicant( 4969): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiP2pService( 1019): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@421c3a48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@421c3a48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@421c3a48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131089
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/GAV2    ( 5049): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/ActivityManager( 1019): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=5154 uid=10011 gids={50011, 3003, 3002, 3001}
W/BluetoothEventManager( 4924): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/BluetoothEventManager( 4924): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422a3ce8:true
,I/CE-BTReceiver( 5154): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.BluetoothPairReceiver: pid=5166 uid=10016 gids={50016, 3002}
,I/ActivityManager( 1019): Killing 4924:com.android.settings/1000 (adj 15): empty #9
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,D/WifiService( 1019): Client connection lost with reason: 4
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 369)
,I/ActivityManager( 1019): Killing 5114:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 80 bytes successfully (thread ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, HTC-HTC One_M8_PT2139
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3584): mHTTPPort  set to : 41277
I/BtConnectorHelper( 3584): Request socket is using : 41277
,I/BtToRequestSocket( 3584): Now accepting connections
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 5 uuid:0000110e-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 6 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 7 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 8 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 9 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 10 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3634): Index: 11 uuid:00006675-7475-7265-6469-616c62756d70
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: 50:2E:6C:AC:21:50
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass1f00
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 5154): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :41277
,I/jxcore-log( 3584): 2015-11-30T11:08:36.486Z SendDataConnector.js: CLIENT connected to 41277, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:36.488Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 41277
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:08:36.500Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,I/jxcore-log( 3584): 2015-11-30T11:08:37.089Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:37.135Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:37.189Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:37.259Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:37.307Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:37.362Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:37.405Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:37.415Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:37.477Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/wpa_supplicant( 4970): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  275): Event received = Trying to associate with,
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 4970): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,I/wpa_supplicant( 4970): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 4970): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  437): NL - Read 312 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 192 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 4970): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  275): Event received = Associated with c0:ff:d4
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 80 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=CONNECTING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 4970): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4970): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  275): Event received = WPA: Key negotiation com
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  275): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  275):  STA Connected !!
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
E/MDMCTBK (  275): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  275): get_freq !!, resp=0
I/MDMCTBK (  275): get_freq !!, Strip data
I/MDMCTBK (  275): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  275): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  275): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
I/MDMCTBK (  275): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1194997248
I/MDMCTBK (  275): return from set_get_from_wpa_supplicant
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  275): wifi_set_tx_pwr: SETTXPOWER = 19
,E/MDMCTBK (  275): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  275): , reply_len: 3, ret: 0
E/MDMCTBK (  275): MdmCutbackHndler, resp=OK
E/MDMCTBK (  275): 
,D/MDMCTBK (  275): wifi_set_tx_pwr: Exit
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: DisconnectedState
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147459
D/WifiStateMachine( 1019): processMsg: DisconnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): Network connection established
,D/WifiStateMachine( 1019): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine( 1019): invokeExitMethods: DisconnectedState
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine( 1019): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine( 1019): invokeEnterMethods: ObtainingIpState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-45ms what=147462 obj=android.net.wifi.StateChangeResult@423a95a8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-39ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@421efab0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=196612
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-4ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 false
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3584): 
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
D/WifiP2pService( 1019): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423df840 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@423df840 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): handleMessage: X
I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
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
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 3
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 3
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 38
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-ADDED 1 38
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  275): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  437): NL - Read 56 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): handleMessage: E msg.what=147461
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiP2pService( 1019): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): handleMessage: X
,D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 20
,D/TCMD    (  437): Listening for incoming client connection request
,D/WifiStateMachine( 1019): addressUpdated: 192.168.1.123/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
,D/WifiStateMachine( 1019): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.123/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): processMsg: ConnectModeState
,D/WifiStateMachine( 1019): processMsg: DriverStartedState
,D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
,D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): handleMessage: X
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196613
,D/WifiStateMachine( 1019): processMsg: ObtainingIpState
D/WifiStateMachine( 1019): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService( 1019): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine( 1019): DHCP successful
,D/WifiStateMachine( 1019): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine( 1019): Calling ARP set with IP = 192.168.1.123
,D/WifiStateMachine( 1019): transitionTo: destState=VerifyingLinkState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: ObtainingIpState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
,D/WifiStateMachine( 1019): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState enter
,D/WifiStateMachine( 1019): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
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
D/WifiStateMachine( 1019): handleMessage: E msg.what=135190
,D/WifiStateMachine( 1019): processMsg: VerifyingLinkState
D/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 1019): transitionTo: destState=CaptivePortalCheckState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
D/WifiStateMachine( 1019): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState enter
,D/WifiStateMachine( 1019): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 1019): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=131092
D/WifiStateMachine( 1019): processMsg: CaptivePortalCheckState
D/WifiStateMachine( 1019): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine( 1019): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService( 1019): WiFi NOT Tethered!
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42025e70
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
D/WifiStateMachine( 1019): transitionTo: destState=ConnectedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
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
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1081): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
D/ConnectivityService( 1019): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService( 1019): WiFi NOT Tethered!
,E/ConnectivityService( 1019): Unexpected mtu value: android.net.wifi.WifiStateTracker@42025e70
I/ModemStatsDSDetect( 1282): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=0
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
D/ConnectivityService( 1019): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=true
,I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1282): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=0
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1448880857506 min interval config: 0 actual interval: 868844
I/CheckinService( 1381): Checking schedule, now: 1448881726354 next: 1448880887486
,I/CheckinService( 1381): active receiver: enabled
,I/CheckinService( 1381): Preparing to send checkin request
,I/EventLogService( 1381): Accumulating logs since 1448880854237
,I/CheckinRequestBuilder( 1381): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1381): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1355): SSL shutdown failed: ssl=0x634fe480: I/O error during system call, Connection timed out
,I/ActivityManager( 1019): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5285 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
,W/dalvikvm( 5285): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5285): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 5285): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5285): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5285): VFY: replacing opcode 0x6e at 0x00ca
,I/MultiDex( 5285): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5285): install
,I/MultiDex( 5285): MultiDexExtractor.load(/data/app/com.google.android.gms-2.apk, false)
,I/MultiDex( 5285): loading existing secondary dex files
,I/MultiDex( 5285): load found 3 secondary dex files
,I/MultiDex( 5285): install done
,D/dalvikvm( 5285): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5285): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5285): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5285): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5285): VFY: unable to resolve instance field 46
,D/dalvikvm( 5285): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5285): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5285): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5285): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5285): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5285): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 5285): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f3e7e8
D/dalvikvm( 5285): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f3e7e8
,D/dalvikvm( 5285): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f3e7e8, skipping init
,D/dalvikvm( 5285): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f3e7e8
D/dalvikvm( 5285): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f3e7e8
,V/JNIHelp ( 5285): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 5285): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x41f3e7e8
,D/dalvikvm( 5285): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x41f3e7e8
D/dalvikvm( 5285): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x41f3e7e8
,D/dalvikvm( 5285): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41f3e7e8
,I/ProviderInstaller( 5285): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1203): callingUid 10022, callindPid: 1203
,E/MDM     ( 1203): [81] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/dalvikvm( 5285): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 5285): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5285): VFY: replacing opcode 0x6e at 0x000d
,D/LocationInitializer( 1381): Restart initialization of location
,D/AuthorizationBluetoothService( 1355): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
I/dalvikvm( 5285): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 5285): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5285): VFY: replacing opcode 0x6e at 0x0220
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1381): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/dalvikvm( 5285): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5285): Link of class 'Lcom/google/android/gms/common/h/c;' failed
E/dalvikvm( 5285): Could not find class 'com.google.android.gms.common.h.c', referenced from method com.google.android.gms.common.h.b.a
W/dalvikvm( 5285): VFY: unable to resolve new-instance 2668 (Lcom/google/android/gms/common/h/c;) in Lcom/google/android/gms/common/h/b;
D/dalvikvm( 5285): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 5285): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.h.b.b
W/dalvikvm( 5285): VFY: unable to resolve virtual method 328: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 5285): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 5285): Failed resolving Lcom/google/android/gms/common/h/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 5285): Link of class 'Lcom/google/android/gms/common/h/c;' failed
,D/dalvikvm( 5285): DexOpt: unable to opt direct call 0x2d44 at 0x02 in Lcom/google/android/gms/common/h/b;.a
,D/ConnectivityService( 1019): NetTransition Wakelock for ConnectedState released by timeout
,W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1355): location=null
,D/WVCdm   (  281): Instantiating CDM.
,I/WVCdm   (  281): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  281): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/DrmWidevineDash(  281): Service_Initialize: widevine DASH app is already open!
D/DrmWidevineDash(  281): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5197000
,E/DrmWidevineDash(  281): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5197000
D/DrmWidevineDash(  281): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  281): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  281): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  281): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  281): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=3466584856
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 5285): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f4c20
D/dalvikvm( 5285): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f4c20
,D/dalvikvm( 5285): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x420f4c20, skipping init
,D/NativeLibraryUtils( 5285): Install completed successfully. count=13 extracted=0
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  281): CdmEngine::OpenSession
,D/DrmWidevineDash(  281): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  281): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  281): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  281): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  281): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  281): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  281): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  281): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  281): PrepareKeyRequest: nonce=810796362
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  281): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  281): CdmEngine::CloseSession
,D/DrmWidevineDash(  281): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  281): OEMCrypto_CloseSession returns 0
,D/dalvikvm( 5285): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 5331): DexOpt: load 4ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 5285): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 5285): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 65ms
,I/Adreno-EGL( 5285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5285): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5285): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5285): Local Branch: 
I/Adreno-EGL( 5285): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5285): Local Patches: NONE
I/Adreno-EGL( 5285): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5285): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5285): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5285): Local Branch: 
I/Adreno-EGL( 5285): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5285): Local Patches: NONE
I/Adreno-EGL( 5285): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5285): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5285): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5285): Local Branch: 
I/Adreno-EGL( 5285): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5285): Local Patches: NONE
I/Adreno-EGL( 5285): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 5285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 5285): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 5285): Build Date: 03/07/14 Fri
I/Adreno-EGL( 5285): Local Branch: 
I/Adreno-EGL( 5285): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 5285): Local Patches: NONE
I/Adreno-EGL( 5285): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 5285): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1381): Classify the device as Phone.
,I/jxcore-log( 3584): DBG, CoordinatorConnector connect called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): Coordinator is now connected to the server!
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/NativeCrypto( 1381): SSL shutdown failed: ssl=0x6a5ed558: I/O error during system call, Connection timed out
,D/WifiStateMachine( 1019): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine( 1019): handleMessage: E msg.what=131215
D/WifiStateMachine( 1019): processMsg: ConnectedState
D/WifiStateMachine( 1019): processMsg: L2ConnectedState
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
,I/CheckinTask( 1381): Sending checkin request (11616 bytes)
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,D/CaptivePortalTracker( 1019): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler },
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/PollingManager( 1533): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
D/PollingManager( 1533): now: 1210731 ,futureTime: 18185425
,D/PollingManager( 1533): Polling alarm set to expire at: 18185425 Current Time: 1210741
,I/openssl ( 4976): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4976): Crypto mode 0 already enabled
I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
D/Tethering( 1019): MasterInitialState.processMessage what=3
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,E/ActivityThread( 1533): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1533): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/PollingManager( 1533): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/OtaApp  ( 1533): [debug] > CusSM.onRadioUp
I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/PollingManager( 1533): now: 1210760 ,futureTime: 18185425
D/PollingManager( 1533): Polling alarm set to expire at: 18185425 Current Time: 1210761
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/ActivityThread( 1533): Failed to find provider info for com.motorola.blur.setupprovider
D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1533): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1533): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1533): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
I/OtaApp  ( 1533): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/dalvikvm( 1533): Jit: resizing JitTable from 4096 to 8192
,D/MobileConnectivityChangeReceiver( 5022): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5022): onReceive CONNECTIVITY_CHANGE networkType=1
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1533): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1533): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/iu.Environment( 5095): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 5095): SYNC; picasa accounts
,D/TelephonyProvider( 1238): Column apn id key is 'apn_id'
,I/iu.UploadsManager( 5095): num queued entries: 0
,I/iu.UploadsManager( 5095): num updated entries: 0
,I/iu.SyncManager( 5095): NEXT; no task
,I/iu.Environment( 1381): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1381): num queued entries: 0
,I/iu.UploadsManager( 1381): num updated entries: 0
,I/iu.SyncManager( 1381): NEXT; no task
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1448880857506 min interval config: 0 actual interval: 871973
,D/DEBUG   ( 1533): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1533): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/GetNotificationsWS( 1533): bindWebServices(): registering our AIDL callback...
,I/SundryService( 1533): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1533): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1533): onServiceConnected()
,D/GetNotificationsWS( 1533): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1533): unbindWebServices(): un-registering our AIDL callback...
I/openssl ( 4976): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4976): Crypto mode 0 already enabled
,D/MobileConnectivityChangeReceiver( 5022): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5022): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinRequestBuilder( 1381): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1381): Failed to find provider info for com.google.android.wearable.settings
,I/iu.Environment( 5095): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/CheckinService( 1381): Checkin interval check for package: unspecified last checkin: 1448880857506 min interval config: 0 actual interval: 872033
,D/DEBUG   ( 1533): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/ContextImpl( 1533): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
,D/dalvikvm( 1019): GC_EXPLICIT freed 1246K, 65% free 17953K/50012K, paused 4ms+9ms, total 93ms
,D/GetNotificationsWS( 1533): bindWebServices(): registering our AIDL callback...
I/SundryService( 1533): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1533): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 1533): onServiceConnected()
,D/GetNotificationsWS( 1533): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 1533): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 1533): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1533): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1533
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 1533): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1533): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1533): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager( 1019): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1533
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1533): [info] > Updatetime from metadata: 10
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1533): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1533): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1533): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Activity reported stop, but no longer stopping: ActivityRecord{424c5c40 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
,I/GCM     ( 1355): Ack for not saved message 20
,I/CheckinRequestBuilder( 1381): Classify the device as Phone.
,I/CheckinTask( 1381): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1381): Checking schedule, now: 1448881729765 next: 1449474799762
,I/CheckinService( 1381): active receiver: disabled
,I/CheckinService( 1381): Checking schedule, now: 1448881729781 next: 1449474799762
,I/CheckinService( 1381): active receiver: disabled
,D/CheckinService( 1381): Recording last checkin time for package unspecified as 1448881729788
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/SBar.NetworkController( 1081): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1081): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
,I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1282): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1081): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1282): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3634): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Entering PendingCommandState State
,I/CE-BTReceiver( 5154): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=10;i.android.bluetooth.device.extra.BOND_STATE=11;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,E/bt-btif ( 3634): services_to_search = 3fffffff
,E/bt-btif ( 3634): ****************search UUID = 1200***********
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): services_to_search = 3ffffffe
,E/bt-btif ( 3634): ****************search UUID = 0100***********
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 373)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 373)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 373
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BTConnectedThread
I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/jxcore-log( 3584): 2015-11-30T11:08:52.539Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btif ( 3634): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 3634): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 3634): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3634): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
D/BluetoothAdapterProperties( 3634): setRemoteTrust() result=true
,D/BluetoothAdapterProperties( 3634): Failed to remove device: 34:FC:EF:11:B1:66
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/BluetoothBondStateMachine( 3634): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3634): StableState(): Entering Off State
,D/BluetoothMetrics( 3634): btclass5a020c
,D/Checkin ( 3634): publish the event [tag = MOT_BT event name = PAIRING]
,I/CE-BTReceiver( 5154): Received Broadcast :#Intent;action=android.bluetooth.device.action.BOND_STATE_CHANGED;launchFlags=0x10;component=com.motorola.context/.publisher.bluetooth.BTReceiver;i.android.bluetooth.device.extra.PREVIOUS_BOND_STATE=11;i.android.bluetooth.device.extra.BOND_STATE=10;i.android.bluetooth.device.extra.REASON=0;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.BOND_STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.BOND_STATE_CHANGED
,I/jxcore-log( 3584): 2015-11-30T11:08:53.346Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.351Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.358Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.372Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.381Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.388Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.397Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.405Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.445Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.484Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.516Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.527Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.566Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.569Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.582Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.586Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.595Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.636Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.646Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.649Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.686Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.696Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.734Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.781Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3584): 
,I/ActivityManager( 1019): Killing 4976:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.846Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.851Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.867Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:08:53.904Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3584): 
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5404 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Launcher( 1294): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Launcher( 1294): Deferring update until onResume
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
,I/Babel   ( 5404): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5404): MmsConfig.loadMmsSettings
I/Babel   ( 5404): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 5404): MmsConfig.loadFromDatabase
,E/Babel   ( 5404): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5404): MmsConfig.loadFromResources
V/GmsNetworkLocationProvi( 1203): DISABLE
,E/Babel   ( 5404): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5404): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/GCoreNlp( 1203): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Settings( 5404): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5441 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 1355): GC_EXPLICIT freed 1529K, 38% free 10797K/17224K, paused 3ms+4ms, total 38ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,I/ActivityManager( 1019): Killing 5003:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5460 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 5022:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/bt-btif ( 3634): dm_pm_timer expires
W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/InternalIcingCorporaPro( 2193): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1381): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5478 uid=10038 gids={50038, 3003, 1028, 1015}
,I/PackageBroadcastService( 1381): Null package name or gms related package.  Ignoreing.
I/ActivityManager( 1019): Killing 5035:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 5095): GC_FOR_ALLOC freed 63K, 3% free 20811K/21288K, paused 25ms, total 27ms
,I/Icing   ( 1381): updateResources: need to parse f{com.google.android.gms}
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/dalvikvm( 1381): GC_CONCURRENT freed 1903K, 33% free 11701K/17224K, paused 3ms+4ms, total 45ms
,I/dalvikvm( 5478): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 5478): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x000e
,W/SQLiteConnectionPool( 1381): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ContactLocale( 5441): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/Finsky  ( 5478): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 5478): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 5478): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 5478): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 5478): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 5478): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 5478): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 5478): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 5478): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5478): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 5478): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5478): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 5478): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5478): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 5478): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 5478): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x0385
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=5515 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/InternalIcingCorporaPro( 2193): UpdateCorporaTask done [took 321 ms] updated apps [took 321 ms] 
,I/dalvikvm( 5478): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 5478): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 5478): Skipping gmscore version check
,D/Finsky  ( 5478): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5478): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 5478): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
W/dalvikvm( 5478): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5478): VFY: replacing opcode 0x6e at 0x0017
,I/ActivityManager( 1019): Killing 5049:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 5515): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f3a458, skipping init
I/openssl ( 5515): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 5515): Crypto mode 0 already enabled
,D/Finsky  ( 5478): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5478): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager( 1019): Killing 5154:com.motorola.context/u0a11 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker( 1019): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1019): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 1019): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 1019): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 1019): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 1019): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 1019): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 1019): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,V/AlarmManager( 1019): sending alarm Alarm{427f2438 type 3 android}
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [b0:c5:59:3f:75:69]: 0, 0, 0
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 25601 ms ago
,I/ActivityManager( 1019): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetooth.BTReceiver: pid=5545 uid=10011 gids={50011, 3003, 3002, 3001}
,D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423d1c70:true
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
I/ActivityManager( 1019): Killing 5166:com.motorola.deviceauthenticator/u0a16 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 377)
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 82 bytes successfully (thread ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 377
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BTConnectedThread
,I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/jxcore-log( 3584): 2015-11-30T11:09:25.276Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3584): 2015-11-30T11:09:26.271Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:26.280Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:26.368Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:26.418Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:26.761Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:26.813Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:26.962Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:26.995Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.180Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.183Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.219Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.224Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.377Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.414Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.477Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.478Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.480Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.481Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.484Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: HTC-HTC One_M8_PT2139
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
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
,I/jxcore-log( 3584): 2015-11-30T11:09:27.943Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:27.950Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T11:09:27.986Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3584): 
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T11:09:28.449Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T11:09:28.676Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:28.828Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:29.306Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:29.563Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:29.612Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:29.645Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:29.719Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:29.800Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:29.869Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:29.887Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.018Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.099Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.174Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.228Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.403Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.412Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.502Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.507Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.587Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3584): 
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/jxcore-log( 3584): 2015-11-30T11:09:30.726Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.876Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.915Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.943Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:30.949Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.035Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.043Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.122Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.189Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.279Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.283Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.314Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.354Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.417Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.457Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:31.495Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:09:32.485Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:32.486Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T11:09:37.489Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:37.490Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:37.491Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:37.493Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: HTC One_M8 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[128]}
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-sdp  ( 3634): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
,E/bt-btif ( 3634): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3634): invalid rfc slot id: 29
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:527)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): shutdown
,I/jxcore-log( 3584): 2015-11-30T11:09:43.013Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:43.015Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:43.017Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): invalid rfc slot id: 24
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): Stop ReceivingThread
,I/BtToSocketBase( 3584): Stop SendingThread
I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:09:43.904Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3584): 2015-11-30T11:09:48.019Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:48.019Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:09:53.022Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:53.024Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:53.025Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:09:53.027Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: HTC One_M8 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[149]}
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,V/AlarmManager( 1019): sending alarm Alarm{43c91650 type 3 android}
E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
W/bt-btif ( 3634): bta_dm_check_av:0
W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3634): L2CAP - con rsp - bad ID. Exp: 5 Got: 4
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 383)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 383
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BTConnectedThread
,I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/jxcore-log( 3584): 2015-11-30T11:10:00.878Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/jxcore-log( 3584): 2015-11-30T11:10:01.290Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 387)
,I/jxcore-log( 3584): 2015-11-30T11:10:01.297Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:01.308Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:01.311Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:01.320Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 80 bytes successfully (thread ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, HTC-HTC One_M8_PT2139
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 46171
,I/BtConnectorHelper( 3584): Request socket is using : 46171
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :46171
,I/jxcore-log( 3584): 2015-11-30T11:10:02.004Z SendDataConnector.js: CLIENT connected to 46171, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:02.006Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 46171
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:10:02.019Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): invalid rfc slot id: 27
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:10:21.739Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand,
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/dalvikvm( 1019): GC_EXPLICIT freed 1558K, 64% free 18017K/50012K, paused 7ms+11ms, total 102ms
,D/dalvikvm( 3634): GC_EXPLICIT freed 2219K, 45% free 9559K/17224K, paused 2ms+5ms, total 32ms
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3634): invalid rfc slot id: 28
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:10:51.695Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:52.080Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:52.081Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:52.083Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:52.085Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:52.087Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3584): Disconnect outgoing peer: HTC-HTC One_M8_PT2139
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x44
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
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1,
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,I/jxcore-log( 3584): 2015-11-30T11:10:57.089Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:10:57.090Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,V/AlarmManager( 1019): sending alarm Alarm{4388fd00 type 3 android}
,I/jxcore-log( 3584): 2015-11-30T11:11:02.094Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:02.095Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:02.096Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:02.098Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: HTC One_M8 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[153]}
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [b0:c5:59:3f:75:69]: 6, f, 6109
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 392)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 392)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:b1:66]: 7, f, 610c
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 393)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 393)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 393
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 393)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, LGE-Nexus 5_PT8981
,I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3584): Creating BTConnectedThread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 393)
,I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/jxcore-log( 3584): 2015-11-30T11:11:05.248Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 82 bytes successfully (thread ID: 392)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 392)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 392
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 392)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 392)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9998 B0:C5:59:3F:75:69]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, samsung-SM-G900F_PT9998
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BTConnectedThread
,I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/jxcore-log( 3584): 2015-11-30T11:11:05.430Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,I/jxcore-log( 3584): 2015-11-30T11:11:05.671Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:05.681Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:05.688Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:05.939Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:05.944Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:05.980Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:05.990Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:06.008Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:06.136Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3584): 
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 400)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 80 bytes successfully (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, HTC-HTC One_M8_PT2139
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 36007
,I/BtConnectorHelper( 3584): Request socket is using : 36007
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :36007
,I/jxcore-log( 3584): 2015-11-30T11:11:13.669Z SendDataConnector.js: CLIENT connected to 36007, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:11:13.670Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 36007
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:11:13.684Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 1
,W/bt-btif ( 3634): invalid rfc slot id: 33
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:11:56.012Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x48
,W/bt-btif ( 3634): invalid rfc slot id: 31
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT9998
,I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:11:56.183Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,V/AlarmManager( 1019): sending alarm Alarm{431032f8 type 3 android}
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229a5c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/jxcore-log( 3584): 2015-11-30T11:12:03.742Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:03.743Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:03.745Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:03.747Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:03.749Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3584): 
,I/BtToSocketBase( 3584): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3584): Disconnect outgoing peer: HTC-HTC One_M8_PT2139
I/BtToSocketBase( 3584): Stop ReceivingThread
I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [34:fc:ef:11:b1:66]: 7, f, 610c
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:255
W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Incoming connection initialized (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesRead: Read 77 bytes successfully (thread ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Got valid identity from [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): removeThreadFromList: Removing thread with ID 404
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Handshake thread disposed (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT8981 34:FC:EF:11:B1:66]
I/BtConnectorHelper( 3584): Starting the connected thread incoming : true, LGE-Nexus 5_PT8981
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BTConnectedThread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 404)
I/BtConnectorHelper( 3584): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3584): --DoOneRunRound started
,I/BtToRequestSocket( 3584): LocalHost address: localhost/127.0.0.1, port: 46601
,I/jxcore-log( 3584): 2015-11-30T11:12:06.759Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): --DoOneRunRound ended
,I/jxcore-log( 3584): 2015-11-30T11:12:07.209Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:07.217Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:07.243Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:07.245Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:08.748Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:08.749Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3584): 2015-11-30T11:12:13.753Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:13.754Z SendDataConnector.js: Connect (retry count 4) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:13.756Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:13.757Z SendDataConnector.js: do connect now
I/jxcore-log( 3584): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Trying to start connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnecting: HTC One_M8 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): connect: Started connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Trying to connect...
,W/BluetoothAdapter( 3584): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3634): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 3584): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[160]}
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): info:x10
,D/        ( 3634): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_CONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3634): process_service_search_attr_rsp
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3634): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Outgoing connection initialized (thread ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesWritten: 81 bytes successfully written (thread ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Entering thread (ID: 409)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): onBytesRead: Read 80 bytes successfully (thread ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3584): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3584): Exiting thread (ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT2139 50:2E:6C:AC:21:50]
,I/BtConnectorHelper( 3584): Starting the connected thread incoming : false, HTC-HTC One_M8_PT2139
I/BtToSocketBase( 3584): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3584): mHTTPPort  set to : 45707
,I/BtConnectorHelper( 3584): Request socket is using : 45707
,I/BtToRequestSocket( 3584): Now accepting connections
,I/BtConnectorHelper( 3584): Calling ConnectionStatusUpdate with port :45707
,I/jxcore-log( 3584): 2015-11-30T11:12:17.232Z SendDataConnector.js: CLIENT connected to 45707, error: null
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:17.234Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): incoming data from: /127.0.0.1, port: 45707
,I/BtToRequestSocket( 3584): Set local streams
,I/jxcore-log( 3584): 2015-11-30T11:12:17.246Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3584): 
,I/BtToRequestSocket( 3584): rin ended ---------------------------;
,D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 1
,W/bt-btif ( 3634): proc dm_pm_timer expires
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/bt-btif ( 3634): dm_pm_timer expires
,W/bt-btif ( 3634): dm_pm_timer expires 0
,W/bt-btif ( 3634): proc dm_pm_timer expires
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
,I/jxcore-log( 3584): timeout now
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): dun
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): weAreDoneNow , resultArray.length: 1
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): done, now sending data to server
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): -- RESULT DATA {"name:":"motorola-XT1039_PT6879","time":1000132,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":3180,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"50:2E:6C:AC:21:50","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:1F:C9:5E","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,
,I/jxcore-log( 3584): sendList : 100% : 3180 ms, 99% : 3180 ms, 95 : 3180 ms, 90% : 3180 ms.
I/jxcore-log( 3584): 
I/jxcore-log( 3584): Result count 1, range 3180 ms to  3180 ms.
I/jxcore-log( 3584): 
I/jxcore-log( 3584): sendList failed peers count : 4 [80 %]
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 50:2E:6C:AC:21:50, Tried : 1
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 34:FC:EF:11:AE:67, Tried : 1
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : B0:C5:59:3F:75:69, Tried : 1
I/jxcore-log( 3584): 
I/jxcore-log( 3584): sendList never tried peers count : 16 [76.19047619047619 %]
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 34:FC:EF:11:B1:66
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3584): 
I/jxcore-log( 3584): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:12:36.833Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3584): 
I/jxcore-log( 3584): 2015-11-30T11:12:36.833Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:12:36.834Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3584): 
I/BtConnectorHelper( 3584): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 3584): Stop ReceivingThread
,I/BtToSocketBase( 3584): Stop SendingThread
I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3584): Close LocalOutputStream
I/BtToSocketBase( 3584): Close localHostSocket
I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3584): Close bt out
I/BtToSocketBase( 3584): Close bt socket
,I/BtToRequestSocket( 3584): Close server socket
,I/jxcore-log( 3584): 2015-11-30T11:12:36.839Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3584): 
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3634): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=0
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3634): invalid rfc slot id: 34
,I/BtToSocketBase( 3584): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8981
,I/BtToSocketBase( 3584): Stop ReceivingThread
,I/BtToSocketBase( 3584): Stop SendingThread
,I/BtToSocketBase( 3584): Close local in
,I/BtToSocketBase( 3584): Close LocalOutputStream
,I/BtToSocketBase( 3584): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3584): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT8981
,I/BtToSocketBase( 3584): Close localHostSocket
,I/BtToSocketBase( 3584): Close bt in
,I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/BtToSocketBase( 3584): Close bt in
I/BtToSocketBase( 3584): Close bt out
,I/BtToSocketBase( 3584): Close bt socket
,I/jxcore-log( 3584): 2015-11-30T11:12:40.066Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3584): 
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f22a14c rs_disc_pending=1
,W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3634): tBTM_SEC_DEV:0x5f229f90 rs_disc_pending=1
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3634): bta_dm_check_av:0
,W/bt-btif ( 3634): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3634): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3634): RFCOMM_DisconnectInd LCID:0x4a
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,E/bt-btm  ( 3634): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothPbapService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,I/CE-BTReceiver( 5545): Received Broadcast :#Intent;action=android.bluetooth.device.action.ACL_DISCONNECTED;launchFlags=0x4000010;component=com.motorola.context/.publisher.bluetooth.BTReceiver;end
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Start Service
,V/BluetoothFtpService( 3634): Ftp Service onStartCommand
,V/BluetoothFtpService( 3634): action: android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,D/BluetoothAdapterService(1106519632)( 3634): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 3634): getBondedDevices: length=1
,V/AlarmManager( 1019): sending alarm Alarm{424c60b0 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4201df58 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{43721110 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427f0d88 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{427e9fa0 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{427cff00 type 1 com.android.deskclock}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5802 uid=10015 gids={50015, 1028}
,I/EventLogService( 1381): Aggregate from 1448881726371 (log), 1448879792368 (data)
,I/ActivityManager( 1019): Killing 5285:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,I/jxcore-log( 3584): DBG, CoordinatorConnector command called
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): stop tests now !
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): stop current!
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): testSendData stopped
I/jxcore-log( 3584): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Shutting down...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:516)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:493)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:395)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:131)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:117)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3584): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3584): onServerStopped
E/bt-btif ( 3634): bta_jv_rfcomm_stop_server
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): setState: INITIALIZED
,I/jxcore-log( 3584): StopBroadcasting went ok
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): 2015-11-30T11:15:57.444Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3584): 
I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onConnectionFailed: Socket is null
,W/jxcore-log( 3584): $$jxcore_callback_48 wasn't registered
W/jxcore-log( 3584): 
,W/jxcore-log( 3584): $$jxcore_callback_48 wasn't registered
W/jxcore-log( 3584): 
,I/jxcore-log( 3584): DBG, CoordinatorConnector command called
I/jxcore-log( 3584): 
I/jxcore-log( 3584): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":3180,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"50:2E:6C:AC:21:50\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:AE:67\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"F8:95:C7:87:85:54\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"00:F4:6F:30:E0:6C\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":
I/jxcore-log( 3584): ****TEST TOOK:  ms ****
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3584): 
I/jxcore-log( 3584): stop tests now !
I/jxcore-log( 3584): 
I/jxcore-log( 3584): end, event received
I/jxcore-log( 3584): 
,I/jxcore-log( 3584): CoordinatorConnector close called
I/jxcore-log( 3584): 
I/jxcore-log( 3584): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3584): 
I/jxcore-log( 3584): The Coordinator has disconnected!
I/jxcore-log( 3584): 
I/jxcore-log( 3584): The Coordinator has closed!
I/jxcore-log( 3584): 
I/jxcore-log( 3584): stop tests now !
I/jxcore-log( 3584): 
I/jxcore-log( 3584): turning Radios off
I/jxcore-log( 3584): 
I/jxcore-log( 3584): Toggling radios to false
I/jxcore-log( 3584): 
D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1019): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4369f738 mBinding = false
,D/BluetoothManagerService( 1019): Message: 2
W/Settings( 1243): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
D/BluetoothManagerService( 1019): Sending off request.
D/BluetoothAdapterState( 3634): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3634): Setting state to 13
I/BluetoothAdapterState( 3634): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3634): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 3634): onBluetoothDisable()
I/BluetoothAdapterState( 3634): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 3634): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 3634): Scan Mode:21
D/BluetoothAdapterState( 3634): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 3634): bta_jv_rfcomm_stop_server
D/btif_config_util( 3634): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 3634): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3634): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3634): bta_jv_rfcomm_stop_server
E/bt-btif ( 3634): bta_jv_rfcomm_stop_server
E/bt-btif ( 3634): bta_jv_rfcomm_stop_server
W/bt-btif ( 3634): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3634): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3634): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothManagerService( 1019): Message: 60
,D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3634): onReceive
,D/BluetoothMapService( 3634): STATE_TURNING_OFF removeTimeoutMsg:false
,D/BluetoothMapService( 3634): MAP Service closeService in
I/ActivityManager( 1019): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5840 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/Settings( 1243): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,D/WifiService( 1019): setWifiEnabled: false pid=3584, uid=10418
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
,I/BtOppRfcommListener( 3634): stopping Accept Thread
,I/BtOppRfcommListener( 3634): BluetoothSocket listen thread finished
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
D/WifiStateMachine( 1019): handleMessage: E msg.what=131084
D/WifiStateMachine( 1019): processMsg: ConnectedState
,D/WifiStateMachine( 1019): processMsg: L2ConnectedState
D/WifiStateMachine( 1019): processMsg: ConnectModeState
D/WifiStateMachine( 1019): processMsg: DriverStartedState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): transitionTo: destState=WaitForP2pDisableState
,D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
,D/WifiStateMachine( 1019): invokeExitMethods: ConnectedState
D/WifiStateMachine( 1019): invokeExitMethods: L2ConnectedState
D/WifiStateMachine( 1019): Stopping DHCP and clearing IP
,D/WifiStateMachine( 1019): setSuspendOptimizationsNative: 1 true
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1243): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
D/WifiP2pService( 1019): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 3584): Radios toggled
I/jxcore-log( 3584): 
I/chromium( 3584): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onBluetoothAdapterScanModeChanged: Mode changed to 21
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/TCMD    (  437): NL - Read 60 bytes from update socket.
D/TCMD    (  437): NL - ignore NL message, type = 21
D/TCMD    (  437): Listening for incoming client connection request
D/WifiStateMachine( 1019): addressRemoved: 192.168.1.123/24 on wlan0 flags 128 scope 0
D/WifiStateMachine( 1019): addressRemoved: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine( 1019): setDetailed state, old =CONNECTED and new state=DISCONNECTED
,D/WifiMetrics( 1019): connected time updated 1282025
D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService( 1019): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
D/ConnectivityService( 1019): Attempting to switch to mobile
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
,D/ConnectivityService( 1019): Attempting to switch to ETHERNET
D/WifiStateMachine( 1019): invokeExitMethods: ConnectModeState
D/WifiStateMachine( 1019): invokeExitMethods: DriverStartedState
D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine( 1019): Unexpected BatchedScanResults :OK
I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1081): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine( 1019): invokeEnterMethods: WaitForP2pDisableState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiP2pService( 1019): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 1019): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): P2pDisablingState
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
,D/WifiP2pService( 1019): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onWifiStateChanged: State changed to 1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3584): onWifiStateChanged: Bluetooth or Wi-Fi disabled, stopping Wi-Fi peer discovery...
D/WifiP2pService( 1019): p2p socket connection lost
,D/WifiP2pService( 1019): P2pDisabledState
D/WifiStateMachine( 1019): handleMessage: E msg.what=131216
D/WifiStateMachine( 1019): processMsg: WaitForP2pDisableState
D/WifiStateMachine( 1019): processMsg: SupplicantStartedState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
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
,W/ContextImpl( 5840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiP2pService( 1019): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1019): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1019): resetConnections(wlan0, 3)
D/NetUtils( 1019): android_net_utils_resetConnections in env=0x611e8160 clazz=0xbfd00001 iface=wlan0 mask=0x3
,D/BluetoothPbapService( 3634): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService( 1019): Message: 20
,D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42859988:true
,I/bt_hwcfg( 3634): hw_epilog_process
W/bt-btif ( 3634): ag scb idx 1 not allocated
E/bt-btif ( 3634): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3634): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3634): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3634): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3634): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3634): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3634): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 5840): Adding local MAP profile
D/BluetoothMap( 5840): Create BluetoothMap proxy object
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService( 1019): Message: 30
,W/ContextImpl( 5840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
V/NativeCrypto( 1355): Read error: ssl=0x634ce818: I/O error during system call, Connection timed out
D/LocalBluetoothProfileManager( 5840): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5840): finishStartingService: stopping service
,D/CommandListener(  273): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1355): SSL shutdown failed: ssl=0x634ce818: I/O error during system call, Broken pipe
,D/WifiStateMachine( 1019): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
I/bt_hwcfg( 3634): hw_epilog_cback Opcode:0x0C03 Status: 0
,I/bt_hci_bdroid( 3634): bt_hc_worker_thread exiting
D/bt_userial_mct( 3634): userial_close
I/bt_userial_mct( 3634): exiting userial_read_thread
,D/bt_userial_mct( 3634): Leaving userial_evt_read_thread()
,I/SBar.NetworkController( 1081): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
,D/WifiStateMachine( 1019): stopping supplicant
,D/Checkin ( 1019): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiStateMachine( 1019): setWifiState: disabling
,D/WifiStateMachine( 1019): handleMessage: X
D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
I/ModemStatsDSDetect( 1282): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=0
W/XTWiFiOS( 1255): Active network info is not available
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange failed
D/ConnectivityService( 1019): Attempting to switch to mobile
E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange failed
D/ConnectivityService( 1019): Attempting to switch to BLUETOOTH_TETHER
D/ConnectivityService( 1019): Attempting to switch to ETHERNET
,I/wpa_supplicant( 4970): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  275):  STA Disconnected !!
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): get_property_value, Enter
I/MDMCTBK (  275): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  275): get_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
I/MDMCTBK (  275): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  275): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  275): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  275): set_property_value, Enter
,I/MDMCTBK (  275): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
I/MDMCTBK (  275): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  275): set_property_value, Exit
E/MDMCTBK (  275): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  275): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
D/TCMD    (  437): NL - Read 68 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
D/TCMD    (  437): Listening for incoming client connection request
,D/Tethering( 1019): InitialState.processMessage what=4
D/WifiStateMachine( 1019): handleMessage: E msg.what=147460
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
D/WifiStateMachine( 1019): handleMessage: X
D/WifiStateMachine( 1019): handleMessage: E msg.what=147462
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,I/SBar.NetworkController( 1081): refreshSignalCluster: wifi: mWifiConnected=false Wifi=(none) Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/Tethering( 1019): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine( 1019): handleMessage: E msg.what=131101
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
D/WifiService( 1019): New client listening to asynchronous messages
,D/BluetoothInputDevice( 5840): Proxy object connected
,D/HidProfile( 5840): Bluetooth service connected
,D/BluetoothPan( 5840): BluetoothPAN Proxy object connected
,D/PanProfile( 5840): Bluetooth service connected
V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothMap( 5840): Proxy object connected
D/MapProfile( 5840): Bluetooth service connected
,D/BluetoothMap( 5840): getConnectedDevices()
,D/BluetoothMap( 5840): Bluetooth is Not enabled
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1019): Killing 5404:com.google.android.talk/u0a70 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Nat464Xlat( 1019): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
I/ModemStatsDSDetect( 1282): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1282): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1282): onReceive() - done, currentInetCondition=0
,I/wpa_supplicant( 4970): eap_proxy Deinitialzed
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
,D/MDMCTBK (  275): Event received = CTRL-EVENT-BSS-REMOVED 0
,D/AndroidRuntime( 5838): 
D/AndroidRuntime( 5838): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5838): CheckJNI is OFF
,D/WifiStateMachine( 1019): handleMessage: E msg.what=196614
,D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
D/WifiStateMachine( 1019): processMsg: DefaultState
,D/WifiStateMachine( 1019): handleMessage: X
,D/dalvikvm( 5838): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5838): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5838): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5838): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 5838): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,I/wpa_supplicant( 4970): wlan0: CTRL-EVENT-TERMINATING 
D/MDMCTBK (  275): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-TERMINATING 
D/MDMCTBK (  275): Event received = CTRL-EVENT-TERMINATING 
D/MDMCTBK (  275):  Wpa Supplicant Exiting !!
D/MDMCTBK (  275): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  275): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  275): wifi_close_sockets: Exit
D/WifiStateMachine( 1019): handleMessage: E msg.what=147458
D/WifiStateMachine( 1019): processMsg: SupplicantStoppingState
,D/WifiStateMachine( 1019): Supplicant connection lost
,D/BTSNOOP-DISP( 3634): btsnoop_close
I/bt_vendor( 3634): cleanup
I/bt_hwcfg( 3634): Starting hciattach daemon
,I/bt_hwcfg( 3634): try to set false
,I/GKI_LINUX( 3634): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3634): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 3634): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3634): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3634): Received stop request...Stopping profile...
D/BluetoothHeadset( 1238): Proxy object disconnected
D/BluetoothHeadset( 1238): Proxy object disconnected
,D/BluetoothHeadset( 1238): Proxy object disconnected
,D/BluetoothHeadset( 1019): Proxy object disconnected
,D/A2dpService( 3634): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3634): Exit Disconnected: -1
,D/dalvikvm( 5838): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,D/BluetoothA2dp( 1019): Proxy object disconnected
,D/BluetoothAdapterService( 3634): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 3634): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3634): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterState( 3634): Stopping profile services that were post enabled
,D/HidService( 3634): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3634): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HealthService( 3634): Received stop request...Stopping profile...
,I/GKI_LINUX( 3634): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3634): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 3634): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/PanService( 3634): Received stop request...Stopping profile...
,D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering( 1019): attempted to stop reverse tether with nothing tethered
D/BluetoothTethering( 1019): Disconnect CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@4349a7f0
D/BluetoothPan( 1019): BluetoothPAN Proxy object disconnected
,D/BluetoothTethering( 1019): got CMD_CHANNEL_DISCONNECTED
,D/BtGatt.DebugUtils( 3634): handleDebugAction() action=null
,D/BtGatt.GattService( 3634): Received stop request...Stopping profile...
D/BtGatt.GattService( 3634): stop()
D/BluetoothInputDevice( 5840): Proxy object disconnected
,D/HidProfile( 5840): Bluetooth service disconnected
D/BluetoothPan( 5840): BluetoothPAN Proxy object disconnected
D/PanProfile( 5840): Bluetooth service disconnected
D/BluetoothMapService( 3634): Received stop request...Stopping profile...
,D/BluetoothMapService( 3634): stop()
,D/BluetoothMapService( 3634): MAP Service closeService in
D/BluetoothMap( 5840): Proxy object disconnected
D/MapProfile( 5840): Bluetooth service disconnected
D/BluetoothAdapterService( 3634): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 3634): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3634): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 3634): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 3634): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 3634): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3634): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 3634): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3634): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3634): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 3634): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 3634): cleanup()
D/BluetoothMapService( 3634): MAP Service closeService in
D/BluetoothAdapterState( 3634): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3634): Setting state to 10
I/BluetoothAdapterState( 3634): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 3634): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService( 1019): Message: 60
I/BluetoothAdapterState( 3634): Entering OffState
D/BluetoothManagerService( 1019): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1019): Broadcasting onBluetoothStateChange(false) to 10 receivers.
D/BluetoothPan( 1019): onBluetoothStateChange on: false
,D/BluetoothPan( 5840): onBluetoothStateChange on: false
,D/BluetoothHeadset( 1238): onBluetoothStateChange: up=false
,D/BluetoothMap( 5840): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1238): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1238): onBluetoothStateChange: up=false
,D/BluetoothPbap( 5840): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1019): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 5840): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1019): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService( 1019): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4369f738 mBinding = false
,D/BluetoothManagerService( 1019): Sending unbind request.
,D/BluetoothAdapterService( 3634): Cleaning up adapter native....
,I/GKI_LINUX( 3634): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3634): GKI_exit_task: GKI_exit_task 1 done
D/BluetoothManagerService( 1019): Bluetooth State Change Intent: 13 -> 10
,I/GKI_LINUX( 3634): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3634): cleanupNative: return from cleanup
,D/BluetoothAdapterService( 3634): Done cleaning up adapter native....
,D/BluetoothAdapterService(1106519632)( 3634): ****onDestroy()********
D/BtGatt.GattService( 3634): cleanup()
W/bt-btif ( 3634): GATTC Module not enabled/already disabled
,W/bt-btif ( 3634): GATTS Module not enabled/already disabled
,D/BluetoothAdapter( 1081): 1107994392: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.sendDeviceAttachIntent:820 com.motorola.authentication.MotAuthenticationService.access$1300:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:575 
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1266 android.content.ContextWrapper.sendBroadcast:370 com.motorola.authentication.MotAuthenticationService.handleKeepDeviceUnlockRequest:732 com.motorola.authentication.MotAuthenticationService.access$1500:60 com.motorola.authentication.MotAuthenticationService$MessageHandler.handleMessage:563 
W/ContextImpl( 5840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 5840): finishStartingService: stopping service
,D/BluetoothAdapter( 1203): 1109663224: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1203): 1109663224: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 5840): 1106554936: getState() :  mService = null. Returning STATE_OFF
V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3634): BluetoothFtpReceiver Stop Service
V/BluetoothFtpService( 3634): Ftp Service onDestroy
V/BluetoothFtpService( 3634): Ftp Service closeService
,E/BluetoothFtpService:RfcommSocketAcceptThread( 3634): Shutdown
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager( 1019): Killing 5441:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.motorola.deviceauthenticator for broadcast com.motorola.deviceauthenticator/.ConnectedUnlockReceiver: pid=5890 uid=10016 gids={50016, 3002}
D/WifiStateMachine( 1019): setWifiState: disabled
D/WifiStateMachine( 1019): transitionTo: destState=InitialState
D/WifiStateMachine( 1019): handleMessage: new destination call exit/enter
D/WifiStateMachine( 1019): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine( 1019): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine( 1019): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine( 1019): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/WifiStateMachine( 1019): invokeEnterMethods: InitialState
W/XTWiFiOS( 1255): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1081): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.NetworkController( 1081): updateTelephonySignalStrength:  No service
W/XTWiFiOS( 1255): Active network info is not available
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange, no information for active_network_info
E/XTCC-3.0.0.2(  552): [WwanPosMgr] handleConnectivtyStatusChange failed
W/Settings( 1203): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange, no information for active_network_info
,E/XTCC-3.0.0.2(  552): [CSMgr] handleConnectivtyStatusChange failed
,D/BluetoothAdapter( 5840): 1106554936: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager( 1019): Killing 5460:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,D/Checkin ( 5890): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DEVAUTH_CONNECT]
W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
E/memtrack( 5838): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5838): failed to load memtrack module: -2
,D/AndroidRuntime( 5838): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10418 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 3584:com.test.thalitest/u0a418 (adj 9): stop com.test.thalitest
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{445fb518 u0 com.test.thalitest/.MainActivity t3}
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1019): WIN DEATH: Window{446d7df8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/PackageSettings( 1019): Skipping PackageSetting{421f6900 com.example.hello/10416} due to missing metadata
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10418 user=0: pkg removed
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1019):   Scheme: "sms"
I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5907 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,W/GeofencerStateMachine( 1203): Ignoring removeGeofence because network location is disabled.
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448882158
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 2159): GC_EXPLICIT freed 7042K, 44% free 9809K/17224K, paused 2ms+8ms, total 50ms
,D/dalvikvm( 1294): GC_EXPLICIT freed 3157K, 33% free 11632K/17224K, paused 2ms+4ms, total 66ms
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
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
I/Launcher( 1294): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,D/dalvikvm( 2193): GC_EXPLICIT freed 3792K, 42% free 10064K/17224K, paused 32ms+6ms, total 122ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
D/dalvikvm( 1019): GC_EXPLICIT freed 1871K, 64% free 18009K/50012K, paused 6ms+12ms, total 175ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 35ms
,I/Launcher( 1294): Deferring update until onResume
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448882158
,D/TCMD    (  437): NL - Read 444 bytes from update socket.
,D/NetlinkEvent(  273): Unexpected netlink message. type=0x11
W/Netd    (  273): No subsystem found in netlink event
D/TCMD    (  437): NL - ignore NL message, type = 17
D/TCMD    (  437): Listening for incoming client connection request
I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  275): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
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
D/VoicemailCleanupService( 5907): Cleaning up data for package: com.test.thalitest
,I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5924 uid=10033 gids={50033, 3003, 1028, 1015}
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10418 #1
,D/TCMD    (  437): NL - Read 1000 bytes from update socket.
D/TCMD    (  437): NL - message type is RTM_NEWLINK
,D/TCMD    (  437): Listening for incoming client connection request
,D/NetlinkEvent(  273): Unexpected netlink message. type=0x11
D/TCMD    (  437): NL - Read 444 bytes from update socket.
W/Netd    (  273): No subsystem found in netlink event
D/TCMD    (  437): NL - ignore NL message, type = 17
D/TCMD    (  437): Listening for incoming client connection request
I/InternalIcingCorporaPro( 2193): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/MDMCTBK (  275): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  275): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  275): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  275): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  275): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
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
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5940 uid=10059 gids={50059, 3003, 1028, 1015}
,D/dalvikvm( 1019): GC_EXPLICIT freed 378K, 65% free 17995K/50012K, paused 4ms+16ms, total 198ms
,I/ActivityManager( 1019): Killing 5095:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 5515:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1243): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/AndroidRuntime( 5838): Shutting down VM
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/dalvikvm( 5838): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,I/ContactLocale( 5907): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/InternalIcingCorporaPro( 2193): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
,W/ActiveOrDefaultContextProvider( 5940): Missing scope.enter somewhere. Returning default context
,D/Checkin ( 2159): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/GAV2    ( 5940): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5963 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/dalvikvm(  278): GC_EXPLICIT freed 44K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,W/ContextImpl( 5963): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
,I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5976 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
E/SQLiteDatabase( 5963): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 5963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5963): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5963): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5963): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 5963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5963): threadid=10: thread exiting with uncaught exception (group=0x41666d40)
E/AndroidRuntime( 5963): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5963): Process: com.android.keychain, PID: 5963
E/AndroidRuntime( 5963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 5963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5963): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5963): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5963): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5963): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 5963): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 5963): Sending signal. PID: 5963 SIG: 9
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 1019): Process com.android.keychain (pid 5963) has died.
W/ActivityManager( 1019): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms

```
