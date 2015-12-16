#### Test 50650278dbf8a2a_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager(  993): sending alarm Alarm{43d18fa0 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3533): 
D/AndroidRuntime( 3533): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3533): CheckJNI is OFF
D/dalvikvm( 3533): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3533): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3533): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3533): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3533): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3533): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3533): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3533): failed to load memtrack module: -2
D/AndroidRuntime( 3533): Calling main entry com.android.commands.am.Am
I/ActivityManager(  993): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3533
W/WindowManager(  993): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  993): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3549 uid=10481 gids={50481, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3533): Shutting down VM
D/dalvikvm( 3533): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3549): Binding Chromium to main looper Looper (main, tid 1) {41fad608}
I/LibraryLoader( 3549): Expected native library version number "",actual native library version number ""
I/chromium( 3549): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3549): Initializing chromium process, renderers=0
D/BluetoothManagerService(  993): Message: 20
D/BluetoothManagerService(  993): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43de4bc0:true
D/BluetoothAdapter( 3549): 1107043672: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3549): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3549): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3549): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3549): Local Branch: 
I/Adreno-EGL( 3549): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3549): Local Patches: NONE
I/Adreno-EGL( 3549): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3549): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3549): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3549): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3549): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3549): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3549): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3549): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3549): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3549): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3549): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3549): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3549): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3549): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3549): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3549): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3549): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3549): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3549): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3549): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3549): CordovaWebView is running on device made by: motorola,
,D/OpenGLRenderer( 3549): Enabling debug mode 0
,W/AwContents( 3549): nativeOnDraw failed; clearing to background color.
,W/AwContents( 3549): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler(  993): Displayed com.test.thalitest/.MainActivity,cp,ca,399
I/ActivityManager(  993): Displayed com.test.thalitest/.MainActivity: +374ms (total +400ms)
W/IInputConnectionWrapper( 3549): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3549): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3549): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fb1ab8
,D/dalvikvm( 3549): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fb1ab8
,D/jxcore_app_log( 3549): JniHelper::setJavaVM(0x41602fa8), pthread_self() = 1614498744
,D/JX-Cordova( 3549): jxcore cordova android initializing
,D/dalvikvm( 3549): GC_CONCURRENT freed 2792K, 17% free 14397K/17224K, paused 1ms+2ms, total 49ms
,D/dalvikvm( 3549): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 3549): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 233K, 17% free 14387K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 195K, 17% free 14412K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3549): Grow heap (frag case) to 16.245MB for 144892-byte allocation
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 258K, 17% free 14459K/17368K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3549): Grow heap (frag case) to 16.360MB for 217334-byte allocation
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 369K, 18% free 14533K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3549): Grow heap (frag case) to 16.535MB for 325996-byte allocation
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 572K, 19% free 14655K/17904K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3549): Grow heap (frag case) to 16.810MB for 488990-byte allocation
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 870K, 20% free 14831K/18384K, paused 26ms, total 26ms
I/dalvikvm-heap( 3549): Grow heap (frag case) to 17.215MB for 733480-byte allocation
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 1294K, 22% free 15089K/19104K, paused 26ms, total 26ms
,D/dalvikvm( 3549): GC_CONCURRENT freed 1676K, 20% free 15460K/19104K, paused 2ms+3ms, total 36ms
D/dalvikvm( 3549): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 3549): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 382K, 20% free 15419K/19104K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3549): Grow heap (frag case) to 18.664MB for 1650320-byte allocation
,D/dalvikvm( 3549): GC_CONCURRENT freed 1721K, 23% free 16005K/20716K, paused 1ms+7ms, total 42ms
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 1357K, 23% free 16068K/20716K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3549): Grow heap (frag case) to 20.084MB for 2475476-byte allocation
,D/dalvikvm( 3549): GC_CONCURRENT freed 1925K, 28% free 16835K/23136K, paused 5ms+5ms, total 58ms
,D/dalvikvm( 3549): GC_CONCURRENT freed 2444K, 27% free 17003K/23136K, paused 2ms+6ms, total 43ms
,D/dalvikvm( 3549): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 381K, 27% free 16941K/23136K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3549): Grow heap (frag case) to 22.118MB for 3713210-byte allocation
,D/dalvikvm( 3549): GC_CONCURRENT freed 2677K, 33% free 18183K/26764K, paused 2ms+6ms, total 59ms
,D/dalvikvm( 3549): GC_FOR_ALLOC freed 726K, 33% free 17991K/26764K, paused 28ms, total 28ms
,W/jxcore-log( 3549): Initializing JXcore engine
,W/jxcore-log( 3549): JXcore engine is ready
,D/dalvikvm( 3549): GC_CONCURRENT freed 360K, 24% free 20607K/26764K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 3549): WAIT_FOR_CONCURRENT_GC blocked 28ms
,W/jxcore-log( 3549): Starting JXcore engine
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
,W/jxcore-log( 3549): Platform android
W/jxcore-log( 3549): 
,W/jxcore-log( 3549): Process ARCH arm
W/jxcore-log( 3549): 
,I/jxcore-log( 3549): JXcore Cordova bridge is ready!
I/jxcore-log( 3549): 
,W/jxcore-log( 3549): JXcore engine is started
,I/chromium( 3549): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3549): Toggling radios to true
I/jxcore-log( 3549): 
,D/BluetoothManagerService(  993): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  993): enable():  mBluetooth =null mBinding = false
,W/Settings( 1256): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothManagerService(  993): Message: 1
,D/BluetoothManagerService(  993): MESSAGE_ENABLE: mBluetooth = null
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,W/XTWiFiOS( 1267): Active network info is not available
,W/Settings( 1256): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/ActivityManager(  993): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3597 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1023}
,D/WifiService(  993): New client listening to asynchronous messages
D/WifiService(  993): setWifiEnabled: true pid=3549, uid=10481
,E/WifiService(  993): Invoking mWifiStateMachine.setWifiEnabled
,W/Settings( 1256): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/WifiStateMachine(  993): setting operational mode to 1
D/WifiStateMachine(  993): handleMessage: E msg.what=131083
,D/WifiStateMachine(  993): processMsg: InitialState
,I/jxcore-log( 3549): Radios toggled
I/jxcore-log( 3549): 
,D/BluetoothManagerService(  993): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
I/jxcore-log( 3549): Got Device Bluetooth address: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3549): 
,W/XTWiFiOS( 1267): Active network info is not available
,I/jxcore-log( 3549): Perf Test app loaded loaded
I/jxcore-log( 3549): 
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,W/Settings( 1256): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:395 android.database.ContentObserver.onChange:129 android.database.ContentObserver$NotificationRunnable.run:180 
,I/jxcore-log( 3549): check test folder
I/jxcore-log( 3549): 
,I/jxcore-log( 3549): found test : ./testFindPeers.js
I/jxcore-log( 3549): 
,D/AdapterServiceConfig( 3597): Adding HeadsetService
D/AdapterServiceConfig( 3597): Adding A2dpService
D/AdapterServiceConfig( 3597): Adding HidService
D/AdapterServiceConfig( 3597): Adding HealthService
D/AdapterServiceConfig( 3597): Adding PanService
D/AdapterServiceConfig( 3597): Adding GattService
,D/AdapterServiceConfig( 3597): Adding BluetoothMapService
,D/BluetoothAdapterService( 3597): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService(  993): Message: 20
,D/BluetoothManagerService(  993): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44429e80:true
,D/BluetoothAdapterState( 3597): make
,I/jxcore-log( 3549): found test : ./testSendData.js
I/jxcore-log( 3549): 
,I/bluedroid( 3597): init
,I/BluetoothAdapterState( 3597): Entering OffState
,I/bte_conf( 3597): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 3597): get_profile_interface socket
,D/BluetoothManagerService(  993): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  993): Message: 40
,D/BluetoothManagerService(  993): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3597): config_hci_snoop_log
,I/GKI_LINUX( 3597): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  993): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  993): Broadcasting onBluetoothServiceUp() to 7 receivers.
,I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 3597): Address is:F4:F1:E1:5C:3B:E2
I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:1 len:6
,D/BluetoothAdapterState( 3597): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3597): Name is: XT1039
,D/BluetoothManagerService(  993): Bluetooth Adapter name changed to XT1039
,D/BluetoothManagerService(  993): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3597): Setting state to 11
I/BluetoothAdapterState( 3597): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 3597): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  993): Message: 60
D/BluetoothManagerService(  993): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  993): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3597): make
,I/BluetoothBondStateMachine( 3597): StableState(): Entering Off State
I/ActivityManager(  993): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3622 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/BluetoothHeadset(  993): Proxy object connected
,D/BluetoothHeadset( 1239): Proxy object connected
,D/BluetoothHeadset( 1239): Proxy object connected
,D/BluetoothHeadset( 1239): Proxy object connected
,D/HeadsetService( 3597): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3597): classInitNative: succeeds
D/HeadsetStateMachine( 3597): Version 1.6
,D/HeadsetStateMachine( 3597): make
,I/BluetoothAdapterState( 3597): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 3597): get_profile_interface handsfree
,D/BluetoothA2dp(  993): Proxy object connected
,D/A2dpService( 3597): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3597): classInitNative: succeeds
V/Avrcp   ( 3597): make
,I/bluedroid( 3597): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 3597): classInitNative: succeeds
,D/A2dpStateMachine( 3597): make
I/bluedroid( 3597): get_profile_interface a2dp
,I/GKI_LINUX( 3597): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 3597): warning : no command pending, ignore ack
,D/A2dpStateMachine( 3597): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3597): classInitNative: succeeds
,D/HidService( 3597): Received start request. Starting profile...
,I/bluedroid( 3597): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3597): classInitNative: succeeds
,D/HealthService( 3597): Received start request. Starting profile...
,I/bluedroid( 3597): get_profile_interface health
,I/BluetoothPanServiceJni( 3597): classInitNative(L105): succeeds
,D/BluetoothPan(  993): BluetoothPAN Proxy object connected
D/PanService( 3597): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3597): initializeNative(L110): pan
,I/bluedroid( 3597): get_profile_interface pan
,D/BluetoothTethering(  993): got CMD_CHANNEL_HALF_CONNECTED
I/BtGatt.JNI( 3597): classInitNative(L684): classInitNative: Success!
,D/BluetoothTethering(  993): CMD_CHANNEL_HALF_CONNECTED: com.android.internal.util.AsyncChannel@43d18720
,D/BtGatt.DebugUtils( 3597): handleDebugAction() action=null
D/BtGatt.GattService( 3597): Received start request. Starting profile...
D/BtGatt.GattService( 3597): start()
,I/bluedroid( 3597): get_profile_interface gatt
,D/BluetoothMapService( 3597): Received start request. Starting profile...
,D/BluetoothMapService( 3597): start()
,D/HeadsetPhoneState( 3597): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 3597): onSignalStrengthsChanged..for signal  prevSignal=0
D/BluetoothAdapterService( 3597): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 3597): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 3597): Profile still not running:com.android.bluetooth.hdp.HealthService
D/HeadsetPhoneState( 3597): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 3597): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3597): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3597): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 3597): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3597): enable
,I/bt_hci_bdroid( 3597): init
I/bt_vendor( 3597): bt-vendor : init
I/bt_hci_bdroid( 3597): ro.qualcomm.hci_transport set to smd
D/bt_userial_mct( 3597): userial_init
I/bt_hci_bdroid( 3597): bt_hc_worker_thread started
I/bt_hwcfg( 3597): Starting hciattach daemon
,I/bt_hwcfg( 3597): try to set false
I/bt_hwcfg( 3597): Starting hciattach daemon
,I/bt_hwcfg( 3597): try to set true
,I/qcom-bluetooth( 3656): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/ActivityManager(  993): Killing 3293:com.android.calendar/u0a7 (adj 15): empty #9
,I/chromium( 3549): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
,E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering(  993): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  993): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiService(  993): New client listening to asynchronous messages
I/qcom-bluetooth( 3663): /system/etc/init.qcom.bt.sh: Transport : smd 
D/Tethering(  993): InitialState.processMessage what=4
D/TCMD    (  497): NL - Read 1004 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
D/TCMD    (  497): Listening for incoming client connection request
D/Tethering(  993): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/Tethering(  993): sendTetherStateChangedBroadcast 0, 0, 0
I/qcom-bluetooth( 3664): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
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
D/TCMD    (  497): NL - Read 1004 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request
,D/QsoftapCmd(  272): Got softap fwreload command we are passing on
,D/SoftapController(  272): Softap fwReload - Ok
,I/qcom-bluetooth( 3668): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 3669): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring down wlan0
,I/qcom-bluetooth( 3671): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,V/BluetoothFtpReceiver( 3597): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,E/WifiHW  (  993): Sanitizing /data/misc/wifi/p2p_supplicant.conf file due to conf version mismatch
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/WifiHW  (  993): ctrl_interface != /data/misc/wifi/sockets
E/Diag_Lib( 3673): qmi_init:  Not initialized, calling process init sequence
E/Diag_Lib( 3673): Setting internal use port to rmnet0
E/Diag_Lib( 3673):  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,E/Diag_Lib( 3673): Failed on DIAG init
E/Diag_Lib( 3673): linux_qmi_qmux_if_client_get_proc_name: pid=3673, proc_name=hci_qcomm_init
E/Diag_Lib( 3673): linux_qmi_qmux_if_client_get_socket_paths: num_grps=2
E/Diag_Lib( 3673): linux_qmi_qmux_if_client_get_proc_group_name: gid=1002, grp_name=bluetooth
E/Diag_Lib( 3673): using socket paths bind=/dev/socket/qmux_bluetooth/qmux_client_socket, connect=/dev/socket/qmux_bluetooth/qmux_connect_socket
E/Diag_Lib( 3673): qmi_client [3673]: successfully connected to server, attempt=1
E/Diag_Lib( 3673): linux_qmi_qmux_if_client_get_client_id [3673]: qmux_client_id=13
E/Diag_Lib( 3673): qmi_client [3673] 13: qmux_client ID is initialized
E/Diag_Lib( 3673): qmi_client [3673] 13: pipe() system call, fd[0]=10, fd[1]=11
,E/Diag_Lib( 3673): qmi_client [3673] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3673): qmi_client [3673] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3673): Sending signal ...... to read cmd data 
E/Diag_Lib( 3673): qmi error code.........:0
E/Diag_Lib( 3673): qmi sys error code.........:0
E/Diag_Lib( 3673): qmi_qmux_if_pwr_up_init_ex:  Successfully created and added QMUX client 19
E/Diag_Lib( 3673): qmi_nas_srvc_init: NAS successfully initialized
E/Diag_Lib( 3673): qmi_qos_srvc_init: QOS successfully initialized
E/Diag_Lib( 3673): qmi_eap_srvc_init: EAP successfully initialized
E/Diag_Lib( 3673): qmi_wds_srvc_init: WDS successfully initialized
E/Diag_Lib( 3673): qmi_atcop_srvc_init: ATCOP successfully initialized
E/Diag_Lib( 3673): qmi_uim_srvc_init: UIM successfully initialized
E/Diag_Lib( 3673): qmi_cat_srvc_init: CAT successfully initialized
E/Diag_Lib( 3673): qmi_init:  Created client handle b7bf0b10
,E/Diag_Lib( 3673): qmi_client [3673] 13: sending 880 bytes on fd = 8
,E/Diag_Lib( 3673): qmi_client [3673] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3673): Sending signal ...... to read cmd data 
E/Diag_Lib( 3673): qmi error code.........:0
,E/Diag_Lib( 3673): qmi sys error code.........:0
E/Diag_Lib( 3673): Setting the api flag to : 1
,E/Diag_Lib( 3673): qmi_client [3673] 13: sending 54 bytes on fd = 8
,I/wpa_supplicant( 3676): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3676): rfkill: Cannot open RFKILL control device
D/TCMD    (  497): NL - Read 1000 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request
D/TCMD    (  497): NL - Read 1000 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request
,E/Diag_Lib( 3676): qmi_init:  Not initialized, calling process init sequence
,E/Diag_Lib( 3676): Setting internal use port to rmnet0
,E/wpa_supplicant( 3676): baseband property is set to [msm]
,D/WifiStateMachine(  993): setWifiState: enabling
,D/WifiStateMachine(  993): Supplicant start successful
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,W/XTWiFiOS( 1267): Active network info is not available
I/rmt_storage(  442): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb74861d0
I/rmt_storage(  442): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  442): wakelock acquired: 1, error no: 42
,I/rmt_storage(  442): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1219993032)
,D/WifiMonitor(  993): startMonitoring(wlan0) with mConnected = false
E/Diag_Lib( 3673): qmi_client [3673] 13: Received 54 bytes on fd = 8
E/Diag_Lib( 3673):  API Flag .............. 1 
,E/Diag_Lib( 3673):  Message ID ............... 92 
,E/wpa_supplicant( 3676):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3676): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3676): card_info[i].card_state: 0x2
E/wpa_supplicant( 3676): card_info[i].error_code: 0x3
E/wpa_supplicant( 3676): SIM/USIM not ready
,E/wpa_supplicant( 3676): Error while reading SIM card status
,E/wpa_supplicant( 3676): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3676): card_info[i].card_state: 0x2
E/wpa_supplicant( 3676): card_info[i].error_code: 0x3
E/wpa_supplicant( 3676): SIM/USIM not ready
,I/wpa_supplicant( 3676): eap_proxy: Card not ready
,E/Diag_Lib( 3673): qmi_service_release called, user_handle=30200
E/Diag_Lib( 3673): qmi_free_srvc_data : ENTRY
E/Diag_Lib( 3673): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib( 3673): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib( 3673): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib( 3673): qmi_service_delete_client_txns : ENTRY - conn_id=0, service=2, client=3
E/Diag_Lib( 3673): qmi_service_delete_client_txns : EXIT
E/Diag_Lib( 3673): qmi_free_srvc_data : EXIT
,E/Diag_Lib( 3673): qmi_client [3673] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3673): qmi_client [3673] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3673): Sending signal ...... to read cmd data 
E/Diag_Lib( 3673): qmi error code.........:0
E/Diag_Lib( 3673): qmi sys error code.........:0
E/Diag_Lib( 3673): qmi_release: Released client handle ff
E/Diag_Lib( 3673): qmi_release: Last client releases, performing library de-init
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=0
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=1
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=2
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=3
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=4
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=5
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=6
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=7
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=8
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=9
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=10
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=11
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=12
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=13
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=14
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=15
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=16
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=17
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=18
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=19
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=20
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=21
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=22
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=23
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=24
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=25
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=26
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=27
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=28
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=29
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=30
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=31
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=32
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=33
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=34
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=35
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=36
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=37
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=38
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=39
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=40
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=41
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=42
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=43
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=44
E/Diag_Lib( 3673): Call,ed qmi_service_reset_all, release on modem=1, conn_id=45
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=46
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=47
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=48
E/Diag_Lib( 3673): Called qmi_service_reset_all, release on modem=1, conn_id=49
E/Diag_Lib( 3673): qmi_nas_srvc_release: NAS successfully released
E/Diag_Lib( 3673): qmi_qos_srvc_release: QOS successfully released
E/Diag_Lib( 3673): qmi_eap_srvc_release: EAP successfully released
E/Diag_Lib( 3673): qmi_wds_srvc_release: WDS successfully released
E/Diag_Lib( 3673): qmi_atcop_srvc_release: ATCOP successfully released
E/Diag_Lib( 3673): qmi_nas_srvc_release: UIM successfully released
E/Diag_Lib( 3673): qmi_cat_srvc_release: CAT successfully released
E/Diag_Lib( 3673): qmi_client [3673] 13: sending 880 bytes on fd = 8
E/Diag_Lib( 3673): qmi_client [3673] 13: Received 880 bytes on fd = 8
E/Diag_Lib( 3673): Sending signal ...... to read cmd data 
E/Diag_Lib( 3673): qmi error code.........:0
E/Diag_Lib( 3673): qmi sys error code.........:0
E/Diag_Lib( 3673): qmi_qmux_if_pwr_down_release: Released QMUX client handle [3673] 13
E/Diag_Lib( 3673): qmi_client [3673] 13: Client release, writing pipe to kill read thread, fd = 11
E/Diag_Lib( 3673): qmi_client [3673] 13: failed to locate client data
E/Diag_Lib( 3673): qmi_client [3673] 13: calling release of fd=8
,E/Diag_Lib( 3673): qmi_qmux_if_pwr_down_release: Last client releases, performing de-init,
,I/rmt_storage(  442): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864,
I/rmt_storage(  442): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  442): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1219993032) wakelock released: 1, error no: 0,
I/rmt_storage(  442): 
,I/rmt_storage(  442): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb74861d0,
,I/wpa_supplicant( 3676): Long line in configuration file truncated,
,I/wpa_supplicant( 3676): rfkill: Cannot open RFKILL control device,
D/TCMD    (  497): NL - Read 1000 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request,
,E/wpa_supplicant( 3676): COUNTRY Code Recived
,E/wpa_supplicant( 3676): COUNTRY Code Recived -COUNTRY PL
,E/wpa_supplicant( 3676): baseband property is set to [msm]
,I/qcom-bluetooth( 3680): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 f4:f1:e1:5c:3b:e2 
,I/qcom-bluetooth( 3681): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,E/wpa_supplicant( 3676):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3676): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3676): card_info[i].card_state: 0x2
E/wpa_supplicant( 3676): card_info[i].error_code: 0x3
E/wpa_supplicant( 3676): SIM/USIM not ready
,E/wpa_supplicant( 3676): Error while reading SIM card status
E/wpa_supplicant( 3676): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 3676): card_info[i].card_state: 0x2
E/wpa_supplicant( 3676): card_info[i].error_code: 0x3
E/wpa_supplicant( 3676): SIM/USIM not ready
,I/wpa_supplicant( 3676): eap_proxy: Card not ready
D/WifiStateMachine(  993): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine(  993): handleMessage: new destination call exit/enter
D/WifiStateMachine(  993): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  993): invokeExitMethods: InitialState
D/WifiStateMachine(  993): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  993): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  993): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131144
D/WifiStateMachine(  993): processMsg: SupplicantStartingState
D/WifiStateMachine(  993): deferMessage: msg=131144
D/WifiStateMachine(  993): handleMessage: X
,D/WifiStateMachine(  993): handleMessage: E msg.what=131085
D/WifiStateMachine(  993): processMsg: SupplicantStartingState
D/WifiStateMachine(  993): deferMessage: msg=131085
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131149
D/WifiStateMachine(  993): processMsg: SupplicantStartingState
D/WifiStateMachine(  993): processMsg: DefaultState
D/WifiStateMachine(  993): setSuspendOptimizations: 2 true
D/WifiStateMachine(  993): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131145
D/WifiStateMachine(  993): processMsg: SupplicantStartingState
D/WifiStateMachine(  993): processMsg: DefaultState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131146
D/WifiStateMachine(  993): processMsg: SupplicantStartingState
D/WifiStateMachine(  993): processMsg: DefaultState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131101
D/WifiStateMachine(  993): processMsg: SupplicantStartingState
D/WifiStateMachine(  993): processMsg: DefaultState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131101
D/WifiStateMachine(  993): processMsg: SupplicantStartingState
D/WifiStateMachine(  993): processMsg: DefaultState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=147457
D/WifiStateMachine(  993): processMsg: SupplicantStartingState
D/WifiStateMachine(  993): Supplicant connection established
,D/WifiStateMachine(  993): setWifiState: enabled
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
I/SBar.NetworkController( 1084): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,W/XTWiFiOS( 1267): Active network info is not available
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiConfigStore(  993): Loading config and enabling all networks
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=false Wifi=zz_moto_stat_sys_wifi_signal_null_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: Signal=(none) Roaming=(none) mSimIconId=(none) Accessibility="Aeroplane mode","No service.","No SIM card."
,I/SBar.NetworkController( 1084): refreshSignalCluster: mobile: mHasMobileDataFeature=true DataTypeShown=(none) Activity=(none) in=false out=false Accessibility="No data."
,D/Checkin ( 2125): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2125): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,E/WifiConfigStore(  993): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,E/wpa_supplicant( 3676): COUNTRY Code Recived -COUNTRY PL
,I/bt_hwcfg( 3597): bluetooth satus is on
I/GKI_LINUX( 3597): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3597): btu_task pending for preload complete event
,D/bt_userial_mct( 3597): userial_open(port:0)
,I/bt_userial_vendor( 3597): Done intiailizing UART
I/bt_userial_vendor( 3597): Done intiailizing UART
I/bt_userial_mct( 3597): CMD=72, EVT=72, ACL_Out=73, ACL_In=73
I/bt_vendor( 3597): Bluetooth Firmware and smd is initialized
D/bt_userial_mct( 3597): Entering userial_read_thread()
,I/bt-btu  ( 3597): btu_task received preload complete event
,D/WifiStateMachine(  993): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  993): handleMessage: new destination call exit/enter
D/WifiStateMachine(  993): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  993): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine(  993): moveTempStackToStateStack: i=1,j=1
D/WifiStateMachine(  993): moveTempStackToStateStack: i=0,j=2
,D/WifiStateMachine(  993): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
,D/WifiStateMachine(  993): invokeEnterMethods: SupplicantStartedState
,D/WifiStateMachine(  993): invokeEnterMethods: DriverStartedState
,D/WifiStateMachine(  993): setDetailed state, old =IDLE and new state=DISCONNECTED
I/        ( 3597): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3597): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3597): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3597): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3597): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3597): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3597): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3597): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3597): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3597): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3597): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3597): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3597): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3597): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3597): BTE_InitTraceLevels -- TRC_BTIF
E/wpa_supplicant( 3676): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/wpa_supplicant( 3676): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiStateMachine(  993): Attempting to reconnect to wifi network ..
,D/WifiStateMachine(  993): transitionTo: destState=DisconnectedState
,D/WifiP2pService(  993): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  993): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  993): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  993): handleMessage: new destination call exit/enter
D/WifiStateMachine(  993): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
D/WifiStateMachine(  993): moveTempStackToStateStack: i=1,j=3
D/WifiStateMachine(  993): moveTempStackToStateStack: i=0,j=4
D/WifiStateMachine(  993): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiStateMachine(  993): invokeEnterMethods: ConnectModeState
D/WifiStateMachine(  993): invokeEnterMethods: DisconnectedState
,D/WifiStateMachine(  993): handleMessage: X
D/CommandListener(  272): Setting iface cfg
,D/CommandListener(  272): Trying to bring up p2p0
D/WifiStateMachine(  993): handleMessage: E msg.what=131144
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131085
,D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131152
D/WifiMonitor(  993): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  993): P2pEnablingState
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
D/WifiP2pService(  993): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  993): P2p socket connection successful
D/WifiP2pService(  993): P2pEnabledState
,D/WifiStateMachine(  993): set country code PL
,D/WifiP2pService(  993): sending p2p connection changed broadcast
E/wpa_supplicant( 3676): COUNTRY Code Recived
E/wpa_supplicant( 3676): COUNTRY Code Recived
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131162
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
D/WifiStateMachine(  993): set frequency band 2
,D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=147462
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED
,D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131167
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
E/SharedPreferencesImpl(  993): Couldn't create directory for SharedPreferences file shared_prefs/wifi_sm_shared_prefs.xml
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=143371
,D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
D/WifiStateMachine(  993): processMsg: SupplicantStartedState
E/bt-btm  ( 3597): BTM_SecRegister:p_cb_info->p_le_callback == 0x5f145049 
E/bt-btm  ( 3597): BTM_SecRegister: btm_cb.api.p_le_callback = 0x5f145049 
D/WifiStateMachine(  993): processMsg: DefaultState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=147462
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  993): processMsg: ConnectModeState
,D/WifiStateMachine(  993): handleMessage: X
,D/WifiP2pService(  993): DeviceAddress: f4:f1:e1:5c:43:c8
E/bt-btif ( 3597): Calling BTA_HhEnable
,D/WifiP2pService(  993): MCC mode enabled 0
E/bt-btif ( 3597): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 3597): Address is:F4:F1:E1:5C:3B:E2
,D/WifiP2pService(  993): mP2pAutoConnectSupport = 0
I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:1 len:6
D/BluetoothAdapterProperties( 3597): Name is: XT1039
I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothManagerService(  993): Bluetooth Adapter name changed to XT1039
D/BluetoothManagerService(  993): Stored Bluetooth name: XT1039
D/BluetoothAdapterProperties( 3597): Scan Mode:21
D/WifiP2pService(  993): sending p2p persistent groups changed broadcast
I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3597): Discoverable Timeout:120
I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:8 len:0
,I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:3 len:48
D/WifiP2pService(  993): InactiveState
D/WifiP2pService(  993): InactiveState{ when=-19ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  993): P2pEnabledState{ when=-19ms what=131207 target=com.android.internal.util.StateMachine$SmHandler }
E/bt_mct  ( 3597): hci lib postload completed
I/bte_conf( 3597): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/WifiP2pService(  993): InactiveState{ when=-20ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  993): P2pEnabledState{ when=-20ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
I/bte_conf( 3597): [1] primary_record=1 vendor_id=0x001D vendor_id_source=0x0001 product_id=0x1200 version=0x1436
E/wpa_supplicant( 3676): COUNTRY Code Recived
I/bte_conf( 3597): Attempt to load did conf from /etc/bluetooth/bt_did.conf
E/wpa_supplicant( 3676): COUNTRY Code Recived
I/bte_conf( 3597): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/WifiP2pService(  993): InactiveState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  993): P2pEnabledState{ when=-8ms what=143376 obj=PL target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterState( 3597): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3597): ScanMode =  21
D/BluetoothAdapterProperties( 3597): State =  11
D/BluetoothAdapterProperties( 3597): Setting state to 12
D/BluetoothPanServiceJni( 3597): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/BluetoothAdapterState( 3597): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 3597): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 3597): Discoverable Timeout:120
D/BluetoothManagerService(  993): Message: 60
D/BluetoothManagerService(  993): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  993): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset(  993): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3597): Entering On State
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
D/BluetoothPan(  993): onBluetoothStateChange on: true
D/BluetoothHeadset( 1239): onBluetoothStateChange: up=true
D/BluetoothA2dp(  993): onBluetoothStateChange: up=true
D/BluetoothManagerService(  993): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService(1107031368)( 3597): Get Bonded Devices being called
D/BluetoothAdapterService(1107031368)( 3597): Get Bonded Devices being called
D/BluetoothMapService( 3597): onReceive
D/BluetoothMapService( 3597): STATE_ON
D/BluetoothManagerService(  993): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1107031368)( 3597): Get Bonded Devices being called
D/BluetoothMapService( 3597): Map Service startRfcommSocketListener
D/BluetoothManagerService(  993): Message: 40
D/BluetoothManagerService(  993): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3597): Map Service initSocket
D/BluetoothManagerService(  993): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3597): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
E/BluetoothServiceJni( 3597): SOCK FLAG = 1 ***********************
D/BluetoothMapService( 3597): Accepting socket connection...
I/BluetoothAdapterProperties( 3597): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 3597): Scan Mode:21
D/BluetoothManagerService(  993): Message: 20
,D/BluetoothManagerService(  993): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4312c8b0:true
,I/qcom-bt-wlan-coex( 3696): /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,D/BluetoothPbapService( 3597): action: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbapService( 3597): Handler(): got msg=1
,D/BluetoothManagerService(  993): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3597): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3597): SOCK FLAG = 1 ***********************
,D/LocalBluetoothProfileManager( 3622): Adding local A2DP profile
,D/BluetoothManagerService(  993): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 3622): Adding local HEADSET profile
,D/BluetoothManagerService(  993): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService(  993): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:256 android.bluetooth.BluetoothInputDevice.<init>:249 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,D/BluetoothManagerService(  993): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:148 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 3622): Adding local MAP profile
D/BluetoothMap( 3622): Create BluetoothMap proxy object
,D/BluetoothManagerService(  993): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1379 
,D/BluetoothManagerService(  993): Message: 30
,W/ContextImpl( 3622): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1672 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 3622): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 3622): finishStartingService: stopping service
,D/BluetoothAdapterService(1107031368)( 3597): Get Bonded Devices being called
,D/BluetoothA2dp( 3622): Proxy object connected
,D/A2dpProfile( 3622): Bluetooth service connected
,D/BluetoothHeadset( 3622): Proxy object connected
,D/HeadsetProfile( 3622): Bluetooth service connected
,D/BluetoothInputDevice( 3622): Proxy object connected
,D/HidProfile( 3622): Bluetooth service connected
,D/BluetoothPan( 3622): BluetoothPAN Proxy object connected
D/PanProfile( 3622): Bluetooth service connected
D/BluetoothMap( 3622): Proxy object connected
D/MapProfile( 3622): Bluetooth service connected
,D/BluetoothMap( 3622): getConnectedDevices()
,D/BluetoothPbap( 3622): Proxy object connected
,D/PbapServerProfile( 3622): Bluetooth service connected
,V/BluetoothFtpReceiver( 3597): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothFtpReceiver( 3597): BluetoothFtpReceiver Start Service
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
,D/BluetoothManagerService(  993): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3597): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 3597): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 3597): Accept thread started.
,V/BluetoothFtpService( 3597): Ftp Service onCreate
I/BluetoothFtpService( 3597): FFFFFtp Service onCreate
,V/BluetoothFtpService( 3597): Starting FTP service
V/BluetoothFtpService( 3597): Ftp Service onStartCommand
V/BluetoothFtpService( 3597): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3597): Handler(): got msg=1
V/BluetoothFtpService( 3597): Ftp Service startRfcommSocketListener
,V/BluetoothFtpService( 3597): Ftp Service initSocket
,D/BluetoothManagerService(  993): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3597): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3597): SOCK FLAG = 3 ***********************
,V/BluetoothFtpService( 3597): Succeed to create listening socket on channel 20
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3597): Run Accept thread
,D/dalvikvm(  993): GC_EXPLICIT freed 22544K, 65% free 17852K/50296K, paused 4ms+9ms, total 137ms
,D/Checkin ( 2125): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 2125): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/MDMCTBK (  274): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  274): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
,I/MDMCTBK (  274): wifi_connect_to_supplicant, current pid is = 274
D/MDMCTBK (  274): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  274): wifi_close_sockets: Exit
,E/MDMCTBK (  274): Attach monitor thread
I/MDMCTBK (  274): createWifiMonitorThread: Started the wifi monitor thread -1221088432
,D/MDMCTBK (  274): wifi_wait_on_socket: Enter monitor thread
,D/TCMD    (  497): NL - Read 1000 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request
,D/Checkin ( 2125): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiP2pService(  993): InactiveState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  993): P2pEnabledState{ when=-1ms what=131207 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  993): P2pEnabledStateupdate channel list
,D/Checkin ( 2125): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c2:ff:d4:d3:aa:48
D/TCMD    (  497): NL - Read 56 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
D/TCMD    (  497): Listening for incoming client connection request
I/wpa_supplicant( 3675): fatal error opening "/sys/power/wake_lock"
I/wpa_supplicant( 3675): fatal error opening "/sys/android_power/acquire_partial_wake_lock"
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48
,D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38:f8:89:11:e9:11
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 06:7c:34:12:7f:81
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 06:7c:34:12:7f:81
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81,
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 9e:93:4e:3e:ba:c5
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 9e:93:4e:3e:ba:c5
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 64:7c:34:b0:03:6e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 64:7c:34:b0:03:6e
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 b8:bc:1b:5a:18:00
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 b8:bc:1b:5a:18:00
D/MDMCTBK (  274): reply_len: 56 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0c:bd:51:2b:c1:25
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 0c:bd:51:2b:c1:25,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE-AUTH 
,D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH 
I/wpa_supplicant( 3676): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  274): Event received = Trying to associate with
,D/WifiStateMachine(  993): handleMessage: E msg.what=147461
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
,D/WifiStateMachine(  993): processMsg: DisconnectedState
,E/wpa_supplicant( 3676): DSDS: eapol_sm_notify_config config->sim_slot = 0
,D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
,D/WifiStateMachine(  993): processMsg: SupplicantStartedState
,D/WifiStateMachine(  993): handleMessage: X
,D/WifiStateMachine(  993): handleMessage: E msg.what=147462
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  993): processMsg: ConnectModeState
,D/WifiStateMachine(  993): handleMessage: X
,I/wpa_supplicant( 3676): WEXT: Custom wireless event: 'BEACONIEs='
I/wpa_supplicant( 3676): WEXT: Custom wireless event: 'BEACONIEs='
D/TCMD    (  497): NL - Read 312 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
D/TCMD    (  497): Listening for incoming client connection request
D/TCMD    (  497): NL - Read 88 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
D/TCMD    (  497): Listening for incoming client connection request
D/TCMD    (  497): NL - Read 68 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
D/TCMD    (  497): Listening for incoming client connection request
D/TCMD    (  497): NL - Read 1000 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3676): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  274): Event received = Associated with c0:ff:d4
D/TCMD    (  497): NL - Read 80 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
D/TCMD    (  497): Listening for incoming client connection request
D/TCMD    (  497): NL - Read 80 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
D/TCMD    (  497): Listening for incoming client connection request
D/TCMD    (  497): NL - Read 68 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiStateMachine(  993): handleMessage: E msg.what=147462
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  993): processMsg: ConnectModeState
,D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=147462
,D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  993): processMsg: ConnectModeState
,D/WifiStateMachine(  993): handleMessage: X
,D/Tethering(  993): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 3676): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3676): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  274): Event received = WPA: Key negotiation com
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  274): Event received = CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  274):  STA Connected !!
D/TCMD    (  497): NL - Read 1000 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request
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
D/WifiStateMachine(  993): handleMessage: E msg.what=147462
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=147459
D/WifiStateMachine(  993): processMsg: DisconnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): Network connection established
,D/WifiStateMachine(  993): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
I/MDMCTBK (  274): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=0, p2p0 = 1, wlan0 = 1, data=0
E/MDMCTBK (  274): cmd: ASSOCFREQ, reply: 0, reply_len: 4, ret: 0
D/MDMCTBK (  274): get_freq !!, resp=0
I/MDMCTBK (  274): get_freq !!, Strip data
I/MDMCTBK (  274): get_freq !!, band = 2, freq = 0
I/MDMCTBK (  274): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=19
,I/MDMCTBK (  274): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): get_property_value, Enter
I/MDMCTBK (  274): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  274): get_property_value, Exit
I/MDMCTBK (  274): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1220936344
I/MDMCTBK (  274): return from set_get_from_wpa_supplicant
I/MDMCTBK (  274): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  274): set_property_value, Enter
I/MDMCTBK (  274): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  274): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  274): set_property_value, Exit
E/MDMCTBK (  274): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  274): wifi_set_tx_pwr: SETTXPOWER = 19
E/MDMCTBK (  274): cmd: DRIVER SETTXPOWER 19, reply: OK
E/MDMCTBK (  274): , reply_len: 3, ret: 0
E/MDMCTBK (  274): MdmCutbackHndler, resp=OK
E/MDMCTBK (  274): 
,D/MDMCTBK (  274): wifi_set_tx_pwr: Exit
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Tethering(  993): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  993): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  993): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  993): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  993): invokeExitMethods: DisconnectedState
D/WifiStateMachine(  993): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  993): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  993): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
D/WifiStateMachine(  993): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  993): invokeEnterMethods: ObtainingIpState
,D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=147462
,D/WifiStateMachine(  993): processMsg: ObtainingIpState
D/WifiStateMachine(  993): ObtainingIpState{ when=-34ms what=147462 obj=android.net.wifi.StateChangeResult@420012f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  993): processMsg: L2ConnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
,D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131101
D/WifiStateMachine(  993): processMsg: ObtainingIpState
D/WifiStateMachine(  993): ObtainingIpState{ when=-28ms what=131101 obj=android.net.wifi.WifiStateMachine$TetherStateChange@422cd960 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  993): processMsg: L2ConnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
D/WifiStateMachine(  993): processMsg: SupplicantStartedState
D/WifiStateMachine(  993): processMsg: DefaultState
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=196612
,D/WifiStateMachine(  993): processMsg: ObtainingIpState
D/WifiStateMachine(  993): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  993): processMsg: L2ConnectedState
,D/WifiStateMachine(  993): setSuspendOptimizationsNative: 1 false
,E/WifiStateMachine(  993): Unexpected BatchedScanResults :OK
D/WifiP2pService(  993): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428068b8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  993): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@428068b8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  993): handleMessage: X
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 1 c2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 2 38
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 3 06
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 4 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 5 9e
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 6 64
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 b8
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 7 b8
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 0c
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-ADDED 8 0c
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  274): Event received = WPS-AP-AVAILABLE-AUTH 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-STATE-CHANGE i
D/MDMCTBK (  274): Event received = CTRL-EVENT-STATE-CHANGE i
D/TCMD    (  497): NL - Read 56 bytes from update socket.
D/TCMD    (  497): NL - message type is RTM_NEWLINK
,D/TCMD    (  497): Listening for incoming client connection request
D/WifiP2pService(  993): InactiveState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  993): P2pEnabledState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  993): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  993): InactiveState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@4436f7c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  993): P2pEnabledState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@4436f7c0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  993): DefaultState{ when=-4ms what=147462 obj=android.net.wifi.StateChangeResult@4436f7c0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  993): handleMessage: E msg.what=147461
D/WifiStateMachine(  993): processMsg: ObtainingIpState
D/WifiStateMachine(  993): ObtainingIpState{ when=-6ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  993): processMsg: L2ConnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
D/WifiStateMachine(  993): processMsg: SupplicantStartedState
,D/WifiStateMachine(  993): handleMessage: X
,D/TCMD    (  497): NL - Read 60 bytes from update socket.
D/TCMD    (  497): NL - ignore NL message, type = 20
,D/TCMD    (  497): Listening for incoming client connection request
,D/WifiStateMachine(  993): addressUpdated: 192.168.1.127/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  993): handleMessage: E msg.what=131215
,D/WifiStateMachine(  993): processMsg: ObtainingIpState
,D/WifiStateMachine(  993): ObtainingIpState{ when=-2ms what=131215 obj=192.168.1.127/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  993): processMsg: L2ConnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
,D/WifiStateMachine(  993): processMsg: DriverStartedState
,D/WifiStateMachine(  993): processMsg: SupplicantStartedState
,D/WifiStateMachine(  993): processMsg: DefaultState
,D/WifiStateMachine(  993): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  993): handleMessage: X
,D/WifiStateMachine(  993): handleMessage: E msg.what=196613
,D/WifiStateMachine(  993): processMsg: ObtainingIpState
,D/WifiStateMachine(  993): ObtainingIpState{ when=-2ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  993): processMsg: L2ConnectedState
,D/WifiStateMachine(  993): setSuspendOptimizationsNative: 1 true
,D/WifiP2pService(  993): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  993): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  993): DHCP successful
D/WifiStateMachine(  993): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  993): Calling ARP set with IP = 192.168.1.127
D/WifiStateMachine(  993): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  993): handleMessage: new destination call exit/enter
D/WifiStateMachine(  993): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  993): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  993): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  993): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=VerifyingLinkState
D/WifiStateMachine(  993): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  993): VerifyingLinkState enter
D/WifiStateMachine(  993): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=151572
D/WifiStateMachine(  993): processMsg: VerifyingLinkState
D/WifiStateMachine(  993): VerifyingLinkState what=151572 NOT_HANDLED
,D/WifiStateMachine(  993): processMsg: L2ConnectedState
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/WifiStateMachine(  993): handleMessage: X
,D/WifiStateMachine(  993): handleMessage: E msg.what=135190
D/WifiStateMachine(  993): processMsg: VerifyingLinkState
D/WifiStateMachine(  993): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  993): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  993): handleMessage: new destination call exit/enter
D/WifiStateMachine(  993): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  993): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  993): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  993): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=CaptivePortalCheckState
,D/WifiStateMachine(  993): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  993): CaptivePortalCheckState enter
,D/WifiStateMachine(  993): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
,D/ConnectivityService(  993): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  993): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  993): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  993): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/WifiStateMachine(  993): handleMessage: X
D/WifiStateMachine(  993): handleMessage: E msg.what=131092
D/WifiStateMachine(  993): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  993): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/WifiStateMachine(  993): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/ConnectivityService(  993): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,I/SBar.NetworkController( 1084): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
V/ConnectivityService(  993): WiFi NOT Tethered!
,I/jxcore-log( 3549): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3549): 
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,E/ConnectivityService(  993): Unexpected mtu value: android.net.wifi.WifiStateTracker@4208e048
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_0_wide Activity=(none) in=false out=false Accessibility="Wi-Fi disconnected."
,D/WifiStateMachine(  993): transitionTo: destState=ConnectedState
,D/WifiStateMachine(  993): handleMessage: new destination call exit/enter
D/WifiStateMachine(  993): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  993): invokeExitMethods: CaptivePortalCheckState
,D/WifiStateMachine(  993): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  993): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
D/WifiStateMachine(  993): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  993): handleMessage: X
,D/WifiStateMachine(  993): handleMessage: E msg.what=131092
D/WifiStateMachine(  993): processMsg: ConnectedState
D/WifiStateMachine(  993): processMsg: L2ConnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
,D/WifiStateMachine(  993): processMsg: SupplicantStartedState
D/WifiStateMachine(  993): processMsg: DefaultState
,D/WifiStateMachine(  993): handleMessage: X
,D/Checkin (  993): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.NetworkController( 1084): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/Nat464Xlat(  993): requiresClat: netType=1, hasIPv4Address=true
,I/SBar.NetworkController( 1084): refreshSignalCluster: wifi: mWifiConnected=true Wifi=zz_moto_stat_sys_wifi_signal_4_fully_wide Activity=(none) in=false out=false Accessibility="Wi-Fi signal full."
,I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  993): ConnectivityChange for WIFI: CONNECTED/CONNECTED
V/ConnectivityService(  993): WiFi NOT Tethered!
E/ConnectivityService(  993): Unexpected mtu value: android.net.wifi.WifiStateTracker@4208e048
,D/ConnectivityService(  993): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  993): requiresClat: netType=1, hasIPv4Address=true
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1286): INET_CONDITION=0 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=0
,D/Tethering(  993): MasterInitialState.processMessage what=3
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false,
,D/PollingManager( 1542): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  993): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        (  993): Setting time of day to sec=1450226487
,W/        (  993): Unable to set rtc to 1450226487: Invalid argument
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/ActivityManager(  993): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=3787 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/PollingManager( 1542): now: 232843 ,futureTime: 68562492
,D/PollingManager( 1542): Polling alarm set to expire at: 68562492 Current Time: 232846
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.CONNECTIVITY_ACTION Received
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 0
,E/ActivityThread( 1542): Failed to find provider info for com.motorola.blur.setupprovider
D/PollingManager( 1542): registerApp(): CCE
I/CCE     ( 1542): _configureNotificationMechanism(): successfully turned off push and starting polling at interval 1440
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
D/CCE     ( 1542): Registering with Alarm Manager to restart CCE
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/MMApiWebService( 1542): Received data connectivity intent from PollingManager .. retry the waiting requests: 2
D/CCE     ( 1542): trying to auto login since I haven't yet and the radio is up now
,D/MMApiProvisionService( 1542): isRequestAllowed(): already have outstanding request ... ignoring request
D/PollingManager( 1542): connectivity_action: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering(  993): MasterInitialState.processMessage what=3
,D/OtaApp  ( 1542): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/CaptivePortalTracker(  993): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/OtaApp  ( 1542): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1542): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/PollingManager( 1542): now: 232915 ,futureTime: 68562492
,D/PollingManager( 1542): Polling alarm set to expire at: 68562492 Current Time: 232917
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: server told to :continue
,D/MMApiWebService( 1542): generating token using payload instead of using session token
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,E/ActivityThread( 1542): Failed to find provider info for com.motorola.blur.setupprovider
D/CCE     ( 1542): trying to auto login since I haven't yet and the radio is up now
D/MMApiProvisionService( 1542): isRequestAllowed(): already have outstanding request ... ignoring request
D/OtaApp  ( 1542): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1542): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU; getDescription's versionBlur_Version.21.1.46.peregrine_reteu.reteuall.en.EU
,I/OtaApp  ( 1542): [info] > CusSM.runStateMachine: found version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU in database with state (QueryingInstall)
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 1542): [debug] > CusSM.runStateMachine: version Blur_Version.21.1.46.peregrine_reteu.reteuall.en.EU download complete, now querying the user
,D/OtaApp  ( 1542): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MMApiWSBase( 1542): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  993): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3826 uid=10056 gids={50056, 3003, 1028, 1015}
I/MMApiWSBase( 1542): doRequest(): url: https://api.svcmot.com:443/v1/dp/devices.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,W/dalvikvm( 1205): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1205): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,W/dalvikvm( 1205): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1205): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1205): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1205): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1205): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 3787): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fb8190, skipping init
I/openssl ( 3787): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3787): Crypto mode 0 already enabled
,I/ActivityManager(  993): Killing 3386:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  993): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=3854 uid=10030 gids={50030, 3003, 1028, 1015}
I/dalvikvm( 1387): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1387): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1387): VFY: replacing opcode 0x6e at 0x003d
,D/TelephonyProvider( 1239): Column apn id key is 'apn_id'
,D/dalvikvm( 1355): null clazz in OP_INSTANCE_OF, single-stepping
,E/ActivityThread( 1387): Failed to find provider info for com.android.contacts.metadata
D/GpsLocationProvider(  993): NTP server returned: 1450226484633 (Wed Dec 16 01:41:24 CET 2015) reference: 229806 certainty: 10 system time offset: -3373
D/DelayedSyncController( 3826): Delaying sync.
E/LocSvc_ApiV02(  993): W/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):453] status = eLOC_CLIENT_SUCCESS, ind..status = eQMI_LOC_GENERAL_FAILURE_V02
,I/dalvikvm( 1205): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1205): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1205): VFY: replacing opcode 0x6e at 0x003d
,V/MmsConfig( 3854): mnc/mcc: 
,E/Auth.Api.Credentials( 1387): [CredentialSyncAdapter] Unknown sync event.
V/MmsConfig( 3854): tag: bool value: enabledMMS - true
V/MmsConfig( 3854): tag: int value: maxMessageSize - 307200
,V/MmsConfig( 3854): tag: int value: maxImageHeight - 1944
V/MmsConfig( 3854): tag: int value: maxImageWidth - 2592
V/MmsConfig( 3854): tag: int value: defaultSMSMessagesPerThread - 500
V/MmsConfig( 3854): tag: int value: defaultMMSMessagesPerThread - 50
V/MmsConfig( 3854): tag: int value: minMessageCountPerThread - 10
V/MmsConfig( 3854): tag: int value: maxMessageCountPerThread - 5000
,V/MmsConfig( 3854): tag: int value: recipientLimit - 20
V/MmsConfig( 3854): tag: bool value: enableMultipartSMS - true
V/MmsConfig( 3854): tag: int value: smsToMmsTextThreshold - 6
V/MmsConfig( 3854): tag: bool value: enableSlideDuration - true
V/MmsConfig( 3854): tag: int value: maxMessageTextSize - -1
V/MmsConfig( 3854): tag: int value: maxSubjectLength - 80
,V/MmsConfig( 3854): tag: bool value: smsForceShowEncodingMenu - true
V/MmsConfig( 3854): tag: bool value: smsForce7BitEncoding - false
D/SyncManager(  993): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 233226, reason: UserStart
V/MmsConfig( 3854): tag: bool value: enableGroupMms - false
,E/MmsConfig( 3854): MmsConfig.loadMmsSettings mms_config.xml missing uaProfUrl setting
,I/ActivityManager(  993): Killing 3047:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  993): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3882 uid=10041 gids={50041, 3003}
,I/ActivityManager(  993): Killing 3408:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1239): GC_EXPLICIT freed 1458K, 45% free 9519K/17224K, paused 12ms+4ms, total 66ms
,D/MobileConnectivityChangeReceiver( 3882): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3882): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 3882): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3882): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  993): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3897 uid=10076 gids={50076, 3003, 1028, 1015}
,I/ActivityManager(  993): Killing 3074:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1387): Checkin interval check for package: unspecified last checkin: 1450212511837 min interval config: 0 actual interval: 13976337
,I/CheckinService( 1387): Checking schedule, now: 1450226488179 next: 1450212541774
,I/CheckinService( 1387): active receiver: enabled
,I/CheckinService( 1387): Preparing to send checkin request
,I/EventLogService( 1387): Accumulating logs since 1450226289184
,D/dalvikvm( 1542): GC_CONCURRENT freed 2330K, 38% free 10722K/17224K, paused 3ms+6ms, total 38ms
,I/CheckinRequestBuilder( 1387): Checkin reason type: 8 attempt count: 1
,D/WifiService(  993): New client listening to asynchronous messages
,E/ActivityThread( 1387): Failed to find provider info for com.google.android.wearable.settings
,D/WifiStateMachine(  993): addressUpdated: fe80::f6f1:e1ff:fe5c:43c7/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  993): handleMessage: E msg.what=131215
D/WifiStateMachine(  993): processMsg: ConnectedState
D/WifiStateMachine(  993): processMsg: L2ConnectedState
D/WifiStateMachine(  993): processMsg: ConnectModeState
D/WifiStateMachine(  993): processMsg: DriverStartedState
,D/WifiStateMachine(  993): processMsg: SupplicantStartedState
,D/WifiStateMachine(  993): processMsg: DefaultState
D/WifiStateMachine(  993): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::f6f1:e1ff:fe5c:43c7/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  993): handleMessage: X
,D/ConnectivityService(  993): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  993):    car=removed=[] added=[fe80::f6f1:e1ff:fe5c:43c7/64,]
,D/Nat464Xlat(  993): requiresClat: netType=1, hasIPv4Address=true
D/ConnectivityService(  993): handleConnectivityChange: address are the same reset per doReset linkProperty[1]: resetMask=0
,D/Nat464Xlat(  993): requiresClat: netType=1, hasIPv4Address=true
,V/WebViewChromiumFactoryProvider( 3897): Binding Chromium to main looper Looper (main, tid 1) {41fb4ee0}
,I/LibraryLoader( 3897): Expected native library version number "",actual native library version number ""
,I/chromium( 3897): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3897): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3897): BLUETOOTH permission is missing!
,D/DelayedSyncController( 3826): Delaying sync.
,D/dalvikvm(  993): GC_EXPLICIT freed 1922K, 65% free 17911K/50296K, paused 6ms+11ms, total 119ms
,I/Adreno-EGL( 3897): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3897): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3897): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3897): Local Branch: 
I/Adreno-EGL( 3897): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3897): Local Patches: NONE
I/Adreno-EGL( 3897): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3897): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3897): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/cutils  (  262): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
,W/Vold    (  262): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3897): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,D/MMApiWSBase( 1542): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1542): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1542): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/NSApplication( 3897): Starting up...
,D/Checkin ( 1542): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1542): handleGetNotificationsResponse(): got 0; more=false
,I/ImageResourceManager( 3093): ImageResourceManager: uninitalized
,I/iu.Environment( 3093): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 3093): SYNC; picasa accounts
,I/ActivityManager(  993): Killing 3435:com.google.android.apps.docs/u0a59 (adj 15): empty #9
I/iu.UploadsManager( 3093): num queued entries: 0
I/iu.UploadsManager( 3093): num updated entries: 0
,I/iu.SyncManager( 3093): NEXT; no task
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/iu.SyncManager( 1387): SYNC; picasa accounts
,D/NetworkLogImpl( 1387): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1387): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1387): num queued entries: 0
,I/iu.UploadsManager( 1387): num updated entries: 0
,I/iu.SyncManager( 1387): NEXT; no task
,D/DEBUG   ( 1542): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,I/SundryService( 1542): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/EmailService.MarketingOptInSetter( 1542): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=1
,I/openssl ( 3787): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3787): Crypto mode 0 already enabled
,D/dalvikvm( 1205): GC_CONCURRENT freed 1637K, 35% free 11337K/17224K, paused 3ms+6ms, total 45ms
,D/MobileConnectivityChangeReceiver( 3882): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3882): onReceive CONNECTIVITY_CHANGE networkType=1
,D/MMApiProvisionService( 1542): ProvisionWS.Response: processing response data: {"sessionToken":"0-62d6271415ae24024c051b549cbffe5b3369896958","error":"OK","sessionExpiration":"46682","deviceId":"1135300315450105856"}
,D/MMApiProvisionService( 1542): ProvisionWS.Response: Completed parsing response.. no settings sent by server
,D/MMApiWSBase( 1542): doRequest(): /v1/dp/devices.json resp length: 137
,D/MMApiProvisionService( 1542): MMApiProvisionService.handleResponse (update_device) : true (None)
,I/iu.Environment( 3093): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/MMApiProvisionService( 1542): handleResponse(): Session Expiration alarm set to expire at: Wed Dec 16 14:39:30 CET 2015
,D/MMApiProvisionService( 1542): _setMMApiCredInfo: storing credential info 
,D/dalvikvm( 1355): GC_CONCURRENT freed 1920K, 40% free 10338K/17224K, paused 2ms+8ms, total 35ms
,I/ActivityManager(  993): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=3956 uid=10007 gids={50007, 3003}
D/dalvikvm( 3093): GC_CONCURRENT freed 617K, 5% free 16454K/17224K, paused 3ms+3ms, total 26ms
E/MMApiProvisionService( 1542): handleResponse(): no settings sent by the server:
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1542): MMApiWebService told us to retry waiting request since device is successfully provisioned: 0
,D/ExtensionsFactory( 3956): No custom extensions.
,I/ActivityManager(  993): Start proc com.android.deskclock for broadcast com.android.deskclock/.AlarmInitReceiver: pid=3973 uid=10015 gids={50015, 1028}
,I/ActivityManager(  993): Killing 3133:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/PhenotypeConfigurator( 1205): Server returned 404
,D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+2ms, total 21ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 17ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 16ms
,I/ActivityManager(  993): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3985 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager(  993): Killing 3622:com.android.settings/1000 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/GCM     ( 1355): GCM config loaded
,D/WifiService(  993): Client connection lost with reason: 4
,V/AlarmClock( 3973): AlarmInitReceiver android.intent.action.TIME_SET
,I/CalendarProvider2( 3985): Created com.android.providers.calendar.CalendarAlarmManager@41fc6138(com.android.providers.calendar.CalendarProvider2@41fbdcf0)
,I/AlarmClock( 3973): Displaying next alarm time: ''
,V/AlarmClock( 3973): AlarmInitReceiver finished
,I/dalvikvm(  993): Jit: resizing JitTable from 8192 to 16384
,I/ActivityManager(  993): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4007 uid=10098 gids={50098}
,D/dalvikvm( 4007): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x41fb1dc0, skipping init
D/TimeService( 4007): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226489188
D/        ( 4007): TimeServiceNative: User Time to be set is 1450226489188
D/QC-time-services( 4007): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4007): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4007): Lib:time_genoff_operation: pargs->ts_val = 1450226489188
,D/QC-time-services(  428): Daemon: Connection accepted:time_genoff
D/QC-time-services(  428): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450226489188
D/QC-time-services(  428): Daemon:genoff_opr: Base = 2, val = 1450226489188, operation = 0
D/QC-time-services(  428): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/16/115 0:35:33
D/QC-time-services(  428): Daemon:Value read from RTC seconds = 1450226133000
D/QC-time-services(  428): Daemon:new time 1450226489188 
D/QC-time-services(  428): Daemon: delta 356188 genoff 356188 
D/QC-time-services(  428): Daemon:genoff_persistent_update: Writing genoff = 356188 to memory
D/QC-time-services(  428): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  428): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 4007): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  428): Updating the TOD offset
D/QC-time-services(  428): Daemon:genoff_persistent_update: Writing genoff = 356188 to memory
D/QC-time-services(  428): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  428): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  428): Daemon:Update to modem bit set
D/QC-time-services(  428): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  428): Daemon: Base = 2, Value being sent to MODEM = 18446743757745107804
,E/QC-time-services( 4007): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  993): Killing 3787:android.process.media/u0a18 (adj 15): empty #9
E/QC-time-services(  428): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  428): Daemon: Time-services: Waiting to acceptconnection
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1387): Checkin interval check for package: unspecified last checkin: 1450212511837 min interval config: 0 actual interval: 13977377
,I/ActivityManager(  993): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4021 uid=10022 gids={50022, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
D/DEBUG   ( 1542): Received intent : com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/SundryService( 1542): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/EmailService.MarketingOptInSetter( 1542): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=1
,D/OtaApp  ( 1542): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1542): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  993): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1542
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
W/dalvikvm( 4021): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 4021): VFY: replacing opcode 0x60 at 0x000b
D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/dalvikvm( 4021): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 4021): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 4021): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 4021): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4021): install
,I/MultiDex( 4021): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,I/MultiDex( 4021): loading existing secondary dex files
,I/MultiDex( 4021): load found 3 secondary dex files
,D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,I/MultiDex( 4021): install done
,D/OtaApp  ( 1542): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS
,D/OtaApp  ( 1542): [debug] > UpdateReceiver: Received True from doSanityCheck.
I/ActivityManager(  993): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_DOWNLOAD_STATUS flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.InstallationActivity (has extras)} from pid 1542
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/IInputConnectionWrapper( 3549): showStatusIcon on inactive InputConnection
,D/dalvikvm( 4021): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4021): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4021): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 4021): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4021): VFY: unable to resolve instance field 36
,D/dalvikvm( 4021): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 4021): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4021): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4021): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 4021): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4021): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 4021): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fb3bf0
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
D/dalvikvm( 4021): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fb3bf0
,D/dalvikvm( 4021): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fb3bf0, skipping init
,D/dalvikvm( 4021): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fb3bf0
D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
D/dalvikvm( 4021): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fb3bf0
,V/JNIHelp ( 4021): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,I/LaunchCheckinHandler(  993): Displayed com.motorola.ccc.ota/.ui.InstallationActivity,wp,wa,127
D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/DEBUG   ( 1542): Received intent : com.motorola.ccc.notification.action.NOTIFY
D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/SundryService( 1542): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1542): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1542): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=0
,D/DEBUG   ( 1542): Received intent : com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SFPerfTracer(  275):      triggers: (rate: 3:30) (compose: 0:4) (post: 0:1) (render: 0:5) (2:129 frames) (3:548)
D/SFPerfTracer(  275):        layers: (0:13) (FocusedStackFrame: 0:10)* (StatusBar: 0:203)* (NavigationBar: 0:38)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:17)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 3:3)* 
,I/ActivityManager(  993): Activity reported stop, but no longer stopping: ActivityRecord{42104868 u0 com.motorola.ccc.ota/.ui.InstallationActivity t2}
D/GetNotificationsWS( 1542): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1542): Implicit intents with startService are not safe: Intent { act=com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC } android.content.ContextWrapper.bindService:517 com.motorola.ccc.notification.GetNotificationsWS.bindWebServices:65 com.motorola.ccc.notification.SundryService.onCreate:1039 
D/GetNotificationsWS( 1542): bindWebServices(): registering our AIDL callback...
I/SundryService( 1542): onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
I/SundryService( 1542): Received shoulder tap
D/GetNotificationsWS( 1542): onServiceConnected()
D/GetNotificationsWS( 1542): onServiceConnected(): Registered for remote service callbacks...
,D/dalvikvm( 4021): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x41fb3bf0
,D/dalvikvm( 4021): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x41fb3bf0
D/dalvikvm( 4021): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x41fb3bf0
,D/dalvikvm( 4021): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x41fb3bf0
,D/WaitableIntentService( 1542): setWaitEnabled(): mWaitCount=1 isWaitEnabled=true
,D/GetNotificationsWS( 1542): GetNotificationsWS.Request: message={"request":{"appendDeviceId":true,"baseUrl":"v1\/ns\/list\/messages","queryParams":{"appid":"MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ"},"httpMethod":"post","requestFormat":"json","wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","isSecure":true,"payload":{"data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"D9DF2F5BB1FA45B0BA459B7FE6942DCD\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}","type":"json"},"retries":"-1","useOAuth":true}}
D/GetNotificationsWS( 1542): sendAidlRequest(): was sent by CCE successfully!
,D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=1
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,I/MMApiWSBase( 1542): doRequest(): url: https://api.svcmot.com:443/v1/ns/list/messages.json/1135300315450105856?appid=MGVKHZWFLNFPYQYLCTOVJLD5LURFMPKZ
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/ProviderInstaller( 4021): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1205): callingUid 10022, callindPid: 1205
,D/LocationInitializer( 1387): Restart initialization of location
,E/MDM     ( 1205): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1355): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1205): No location to return for getLastLocation()
,W/FusedLocationProvider( 1205): location=null
I/dalvikvm( 4021): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 4021): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4021): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 4021): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 4021): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4021): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 4021): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4021): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4021): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4021): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 4021): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 4021): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 4021): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 4021): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 4021): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 4021): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 4021): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,D/ConnectivityService(  993): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1084): the netConditon of netType 1 is updated as 1 by android.net.conn.INET_CONDITION_ACTION,icon color should be blue.
I/PhenotypeConfigurator( 1205): Scheduling Phenotype for one-off execution 2683 seconds from now (1450226489623)
I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1286): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1286): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=100
I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,D/GetConfigurationSnapshotOperation( 1205): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): Level3 Library Nov 20 2013 18:09:31
,I/PhenotypeFlagCommitter( 1205): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
D/DrmWidevineDash(  280): calling OEMCrypto_Initialize, g_qsee_apps_version = 7
D/QSEECOMAPI: (  280): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  280): App is not loaded in QSEE
E/QSEECOMAPI: (  280): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  280): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  280): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  280): App is not loaded in QSEE
E/QSEECOMAPI: (  280): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  280): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  280): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  280): App is not loaded in QSEE
,I/GoogleURLConnFactory( 1205): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  280): Loaded image: APP id = 3
D/DrmWidevineDash(  280): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5239000
,E/DrmWidevineDash(  280): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5239000
,D/DrmWidevineDash(  280): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_APIVersion...
D/DrmWidevineDash(  280): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  280): calling OEMCrypto_IsKeyboxValid...
,D/NativeLibraryUtils( 4021): Install completed successfully. count=14 extracted=0
,D/DrmWidevineDash(  280): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  280): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=2327150745
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4021): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42205278
D/dalvikvm( 4021): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42205278
,D/dalvikvm( 4021): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42205278, skipping init
,D/MMApiWSBase( 1542): doRequest(): v1/ns/list/messages resp length: 1465
,D/CCE     ( 1542): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,D/CCE     ( 1542): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/Checkin ( 1542): publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,D/SundryService( 1542): handleGetNotificationsResponse(): got 0; more=false
,D/DEBUG   ( 1542): Received intent : com.motorola.ccc.notification.action.NOTIFY
I/SundryService( 1542): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 1542): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 1542): onHandleIntent(): isWaitEnabled=false
,D/WaitableIntentService( 1542): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 1542): unbindWebServices(): un-registering our AIDL callback...
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,I/CalendarProvider2( 3985): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3985): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 3956): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3956): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 1205): GC_CONCURRENT freed 1562K, 32% free 11761K/17224K, paused 4ms+8ms, total 39ms
,D/dalvikvm( 4021): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/dalvikvm( 4055): DexOpt: load 3ms, verify+opt 5ms, 128132 bytes
,D/dalvikvm( 4021): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4021): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 68ms
,I/Adreno-EGL( 4021): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4021): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4021): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4021): Local Branch: 
I/Adreno-EGL( 4021): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4021): Local Patches: NONE
I/Adreno-EGL( 4021): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4021): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4021): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4021): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4021): Local Branch: 
I/Adreno-EGL( 4021): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4021): Local Patches: NONE
I/Adreno-EGL( 4021): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/Settings( 4021): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  280): CdmEngine::OpenSession
,D/DrmWidevineDash(  280): calling OEMCrypto_OpenSession...
D/DrmWidevineDash(  280): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  280): OEMCrypto_OpenSession returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetRandom...
,D/DrmWidevineDash(  280): OEMCrypto_GetRandom returns 0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  280): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  280): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateNonce. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  280): PrepareKeyRequest: nonce=966414259
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  280): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  280): CdmEngine::CloseSession
,D/DrmWidevineDash(  280): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  280): OEMCrypto_CloseSession returns 0
,I/Adreno-EGL( 4021): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4021): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4021): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4021): Local Branch: 
I/Adreno-EGL( 4021): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4021): Local Patches: NONE
I/Adreno-EGL( 4021): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/Adreno-EGL( 4021): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4021): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4021): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4021): Local Branch: 
I/Adreno-EGL( 4021): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4021): Local Patches: NONE
I/Adreno-EGL( 4021): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,I/CheckinRequestBuilder( 1387): Classify the device as Phone.
,D/dalvikvm( 1387): GC_CONCURRENT freed 1783K, 31% free 12012K/17224K, paused 3ms+6ms, total 40ms
,I/CheckinTask( 1387): Sending checkin request (12069 bytes)
,I/CheckinResponseProcessor( 1387): From server: 3 gservices updates and 0 deletes
,E/UlpEngine(  993): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,E/UlpEngine(  993): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
,E/UlpEngine(  993): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,E/UlpEngine(  993): kvs.containsKey(ENH_LOCATION_SERVICES_ENABLED) returned false
,W/XTWiFiOS( 1267): No entry in secure settings for enhanced location services: false
I/CertBlacklister(  993): Certificate blacklist changed, updating...
I/CertBlacklister(  993): Certificate blacklist updated
,I/GservicesProvider( 1355): main difference update completed
,I/ActivityManager(  993): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4095 uid=10009 gids={50009, 3003, 2001}
I/CheckinRequestBuilder( 1387): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1387): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm(  993): GC_EXPLICIT freed 780K, 65% free 17929K/50296K, paused 4ms+11ms, total 91ms
,W/ContextImpl( 4095): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4095): Update started
,E/UpdateRequestReceiver( 4095): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  993): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4117 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,W/ContextImpl( 4095): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4095): Update started
,E/UpdateRequestReceiver( 4095): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4095): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4095): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  993): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4139 uid=10025 gids={50025, 3003}
,D/dalvikvm( 4117): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fb7328, skipping init
I/openssl ( 4117): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4117): Crypto mode 0 already enabled
I/ContactAccountLoggerTas( 2158): canRun() : Opted Out
,I/Search.GservicesUpdateTask( 2158): Updating Gservices keys
,I/CheckinRequestBuilder( 1387): Classify the device as Phone.
,I/CheckinTask( 1387): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1387): Checking schedule, now: 1450226492693 next: 1450819562661
,I/CheckinService( 1387): active receiver: disabled
,I/ContactAccountLoggerTas( 2158): canRun() : Opted Out
,I/ContactAccountLoggerTas( 2158): canRun() : Opted Out
,D/CheckinService( 1387): Recording last checkin time for package unspecified as 1450226492712
,I/ContactAccountLoggerTas( 2158): canRun() : Opted Out
,I/DownloadManager( 4117): Download 298 starting
,D/dalvikvm( 1355): GC_EXPLICIT freed 1483K, 40% free 10413K/17224K, paused 2ms+7ms, total 40ms
,W/ActivityThread( 4117): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/DownloadManager( 4117): Download 299 starting
,I/ActivityManager(  993): Killing 3854:com.android.mms/u0a30 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/CheckinService( 1387): Checkin interval check for package: unspecified last checkin: 1450226492712 min interval config: 0 actual interval: 118
I/ActivityManager(  993): Killing 3826:com.android.chrome/u0a56 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3093): GC_FOR_ALLOC freed 164K, 5% free 16522K/17224K, paused 25ms, total 26ms
I/CheckinService( 1387): Checking schedule, now: 1450226492853 next: 1450819562661
I/CheckinService( 1387): active receiver: disabled
I/SystemUpdateService( 1387): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1387): onCreate
,D/SystemUpdateService( 1387): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/dalvikvm( 1387): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 1387): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 1387): VFY: replacing opcode 0x71 at 0x004e
,I/SystemUpdateService( 1387): cancelUpdate (empty URL)
,I/SystemUpdateService( 1387): active receiver: disabled
,D/dalvikvm( 3093): GC_FOR_ALLOC freed 14K, 4% free 18313K/19004K, paused 15ms, total 15ms
,I/Auth    ( 1355): [BroadcastManager] Broadcasting account services changed.
,D/dalvikvm( 1355): GC_EXPLICIT freed 277K, 40% free 10363K/17224K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 1387): GC_EXPLICIT freed 1492K, 30% free 12126K/17224K, paused 4ms+8ms, total 63ms
,W/SQLiteConnectionPool( 1387): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/DownloadManager( 4117): Ignoring Content-Length since Transfer-Encoding is also defined
,D/SystemUpdateService( 1387): onDestroy
,D/Checkin ( 4117): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,E/DynamiteModule( 1387): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1387): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 1387): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1387): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 1387): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 1387): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1387): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1387): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1387): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1387): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1387): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1387): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/DynamiteModule( 1387): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/DynamiteModule( 1387): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/DynamiteModule( 1387): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1387): 	at android.os.Looper.loop(Looper.java:136)
E/DynamiteModule( 1387): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/DynamiteModule( 1387): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 1387): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 1387): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/DynamiteModule( 1387): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/DynamiteModule( 1387): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 1387): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1387): Selected local version of com.google.android.gms.flags
I/DownloadManager( 4117): Download 299 finished with status SUCCESS
,D/SystemEventReceiver( 1387): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1387): Updating ocr activity enabled=false
,I/DownloadManager( 4117): Ignoring Content-Length since Transfer-Encoding is also defined
,I/Auth    ( 1355): [BroadcastManager] Broadcasting account services changed.
W/ActivityManager(  993): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1387): Updating downloaded model state (gservices changed)
,D/GCM     ( 1355): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/Checkin ( 4117): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4117): Download 298 finished with status SUCCESS
,I/ActivityManager(  993): Killing 3897:com.google.android.apps.magazines/u0a76 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1355): GC_EXPLICIT freed 263K, 40% free 10396K/17224K, paused 2ms+6ms, total 40ms
,E/dalvikvm( 1205): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
W/dalvikvm( 1205): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/dalvikvm( 1205): VFY: replacing opcode 0x1f at 0x001a
,D/dalvikvm( 1205): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm( 1205): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
W/dalvikvm( 1205): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1205): VFY: replacing opcode 0x6e at 0x0012
,D/dalvikvm(  993): GC_EXPLICIT freed 926K, 65% free 17786K/50296K, paused 5ms+9ms, total 94ms
,I/GCoreUlr( 1205): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1205): DispatchingService.onCreate()
,D/dalvikvm( 1387): GC_CONCURRENT freed 2005K, 31% free 12053K/17224K, paused 4ms+10ms, total 64ms
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1205): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1205): Ignoring removeGeofence because network location is disabled.
,W/ContextImpl( 4095): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,E/ctxmgr  ( 1205): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/dalvikvm( 1205): GC_CONCURRENT freed 2100K, 33% free 11609K/17224K, paused 3ms+6ms, total 41ms
,W/ctxmgr  ( 1205): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10022, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1205): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/openssl ( 4117): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 4117): Crypto mode 0 already enabled
W/ContextImpl( 4095): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/DownloadManager( 4117): Download 300 starting
,I/GCoreUlr( 1205): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1205): Unbound from all location providers
,I/GCoreUlr( 1205): Place inference reporting - stopped
,I/ContactAccountLoggerTas( 2158): canRun() : Opted Out
,I/DownloadManager( 4117): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 4117): Download 301 starting
,I/GCoreUlr( 1205): DispatchingService.onDestroy()
,I/GCoreUlr( 1205): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1205): Unbound from all location providers
,I/GCoreUlr( 1205): Place inference reporting - stopped
,I/DownloadManager( 4117): Ignoring Content-Length since Transfer-Encoding is also defined
,D/dalvikvm( 1355): GC_EXPLICIT freed 514K, 40% free 10391K/17224K, paused 4ms+5ms, total 42ms
,D/Checkin ( 4117): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/DownloadManager( 4117): Download 300 finished with status SUCCESS
,W/ContextImpl( 4095): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4095): Update downloaded, starting installation
,D/Checkin ( 4117): publish the event [tag = MOT_MEDIA_STATS_L3 event name = FILE_DOWNLOAD]
,I/UpdateFetcherService( 4095): Started installation
,I/DownloadManager( 4117): Download 301 finished with status SUCCESS
,W/ContextImpl( 4095): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4095): Update downloaded, starting installation
,I/UpdateFetcherService( 4095): Started installation
,I/ConfigUpdateInstallReceiver(  993): Not installing, new version is <= current version
,I/GlobalDismissManager( 3956): no sender configured
,D/AlertService( 3956): Beginning updateAlertNotification
,D/AlertService( 3956): No fired or scheduled alerts
,D/AlertService( 3956): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3956): No events found starting within 1 week.
I/ActivityManager(  993): Killing 3985:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  993): Killing 4007:com.qualcomm.timeservice/u0a98 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/CaptivePortalTracker(  993): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  993): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  993): Checking http://216.58.209.78/generate_204
,W/ActivityThread(  993): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/GAV2    ( 3093): Thread[GAThread,5,main]: No campaign data found.
,D/CaptivePortalTracker(  993): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  993): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  993): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  993): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  993): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/InputReader(  993): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  993): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4275 uid=10070 gids={50070, 3003, 1028, 1015, 3002}
,I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "sms"
,I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "smsto"
,I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "mms"
,I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "mmsto"
,I/Launcher( 1291): Deferring update until onResume
,I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "sms"
,I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "smsto"
,I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "mms"
I/Launcher( 1291): Deferring update until onResume
,I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "mmsto"
,I/GCoreNlp( 1205): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel   ( 4275): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4275): MmsConfig.loadMmsSettings
I/Babel   ( 4275): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,I/Babel   ( 4275): MmsConfig.loadFromDatabase
,E/Babel   ( 4275): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4275): MmsConfig.loadFromResources
,E/Babel   ( 4275): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4275): MmsConfig.loadMmsSettings: mUserAgent=motoxt1039, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1039/Profile/motoxt1039.rdf
,W/Settings( 4275): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm(  993): GC_EXPLICIT freed 1593K, 65% free 18013K/50296K, paused 4ms+9ms, total 90ms
,I/ActivityManager(  993): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4311 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
,I/ActivityManager(  993): Killing 3973:com.android.deskclock/u0a15 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager(  993): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4330 uid=10033 gids={50033, 3003, 1028, 1015}
,I/ActivityManager(  993): Killing 3956:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/InternalIcingCorporaPro( 2158): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  993): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4349 uid=10038 gids={50038, 3003, 1028, 1015}
,I/ActivityManager(  993): Killing 4139:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ContactLocale( 4311): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/dalvikvm( 4349): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 4349): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 4349): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4349): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 4349): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x01d3
,I/InternalIcingCorporaPro( 2158): UpdateCorporaTask done [took 219 ms] updated apps [took 219 ms] 
I/dalvikvm( 4349): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4349): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 4349): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4349): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4349): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 4349): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4349): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4349): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4349): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 4349): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4349): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4349): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4349): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 4349): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4349): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x0019
,D/Ads     ( 4349): Skipping gmscore version check
,D/Finsky  ( 4349): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4349): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4349): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/dalvikvm( 4349): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.utils.IntentUtils.access$200
,W/dalvikvm( 4349): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x0017
,D/PackageBroadcastService( 1387): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1387): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 4349): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 1387): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  993): Killing 3882:com.google.android.setupwizard/u0a41 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/Icing   ( 1387): Indexing 35B2C5A8CE535741260EC99169D5C2AD9821FC7E from com.google.android.gms
,D/Icing   ( 1387): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1387): Indexing done 35B2C5A8CE535741260EC99169D5C2AD9821FC7E
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450226500
,W/PackageSettings(  993): Skipping PackageSetting{42272ea0 com.example.hello/10480} due to missing metadata
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{4212c2f0 type 2 android}
,V/AlarmManager(  993): sending alarm Alarm{42122030 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{42313dd8 type 2 android}
,E/ActivityThread( 1387): Failed to find provider info for com.android.contacts.metadata
D/SyncManager(  993): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 293372, reason: UserStart
,V/AlarmManager(  993): sending alarm Alarm{4280f100 type 2 android}
,V/AlarmManager(  993): sending alarm Alarm{42185ea8 type 3 android}
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
,I/ClearcutLoggerApiImpl( 1355): disconnect managed GoogleApiClient
,V/AlarmManager(  993): sending alarm Alarm{427caa38 type 3 android}
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
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5 ,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6 
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7 ,
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 0
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  274): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  274): Event received = CTRL-EVENT-BSS-REMOVED 8
,I/jxcore-log( 3549): Connected to the server!
I/jxcore-log( 3549): 
,I/chromium( 3549): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{42928520 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{42115600 type 1 com.android.deskclock}
,I/ActivityManager(  993): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4424 uid=10015 gids={50015, 1028}
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 37ms
,I/ActivityManager(  993): Killing 4095:com.google.android.configupdater/u0a9 (adj 15): empty #9
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+11ms, total 32ms
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+11ms, total 33ms
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
,V/AlarmManager(  993): sending alarm Alarm{435bf820 type 3 android}
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
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  993): sending alarm Alarm{43198770 type 3 android}
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
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{427a0708 type 3 android}
,V/AlarmManager(  993): sending alarm Alarm{43a0e540 type 2 android}
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
,V/AlarmManager(  993): sending alarm Alarm{43e552f8 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{431eee78 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{438c25a0 type 3 android}
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
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{43263538 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{427b8c30 type 3 android}
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
,I/MDMCTBK (  274): checkDefaultInst, pid match
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
,V/AlarmManager(  993): sending alarm Alarm{4318fb48 type 3 android}
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
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{442cb920 type 3 android}
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
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{430f2be8 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{4210d808 type 2 android}
,D/ConnectivityService(  993): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  993): sending alarm Alarm{420f86d8 type 2 com.google.android.gms}
,D/ConnectivityService(  993): Done.
,D/ConnectivityService(  993): Setting timer for 720seconds
,D/ConnectivityService(  993): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1084): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1286): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1084): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1286): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1286): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1084): updateTelephonySignalStrength:  No service
,V/AlarmManager(  993): sending alarm Alarm{43dd3dd8 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{43d59668 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{4391faa0 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{4297b088 type 3 android}
,V/AlarmManager(  993): sending alarm Alarm{43dd3eb0 type 1 com.android.deskclock}
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
,V/AlarmManager(  993): sending alarm Alarm{420f0700 type 3 android}
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
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{42955518 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{4308d780 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{43026a90 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{4302a8d0 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{43d16b10 type 3 android}
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
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{4434caa0 type 3 android}
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
,V/AlarmManager(  993): sending alarm Alarm{4298a120 type 3 android}
,I/ProcessStatsService(  993): Prepared write state in 40ms
,I/ProcessStatsService(  993): Prepared write state in 24ms
,I/ProcessStatsService(  993): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-18-00.bin
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
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  993): sending alarm Alarm{442c4038 type 3 android}
,V/AlarmManager(  993): sending alarm Alarm{435c5820 type 3 android}
,V/AlarmManager(  993): sending alarm Alarm{442c1490 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4545): 
D/AndroidRuntime( 4545): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4545): CheckJNI is OFF
D/dalvikvm( 4545): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4545): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4545): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4545): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4545): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4545): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4545): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4545): failed to load memtrack module: -2
D/AndroidRuntime( 4545): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  993): Force stopping com.test.thalitest appid=10481 user=-1: uninstall pkg
I/ActivityManager(  993): Killing 3549:com.test.thalitest/u0a481 (adj 9): stop com.test.thalitest
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager(  993):   Force finishing activity ActivityRecord{442bdc40 u0 com.test.thalitest/.MainActivity t3}
I/WindowState(  993): WIN DEATH: Window{442d8a70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  993): Client connection lost with reason: 4
D/dalvikvm(  993): GC_CONCURRENT freed 2160K, 65% free 18095K/50296K, paused 5ms+9ms, total 86ms
W/PackageSettings(  993): Skipping PackageSetting{42272ea0 com.example.hello/10480} due to missing metadata
I/ActivityManager(  993): Force stopping com.test.thalitest appid=10481 user=0: pkg removed
I/InputReader(  993): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "sms"
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450228284
D/dalvikvm( 2125): GC_EXPLICIT freed 6286K, 44% free 9742K/17224K, paused 39ms+6ms, total 86ms
D/dalvikvm( 1291): GC_EXPLICIT freed 2895K, 33% free 11594K/17224K, paused 2ms+71ms, total 133ms
D/BackupManagerService(  993): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Launcher( 1291): Deferring update until onResume
D/dalvikvm( 2158): GC_EXPLICIT freed 3611K, 42% free 10081K/17224K, paused 2ms+5ms, total 142ms
D/dalvikvm( 1387): GC_EXPLICIT freed 1428K, 31% free 12002K/17224K, paused 4ms+7ms, total 180ms
V/BackupManagerService(  993): removePackageParticipantsLocked: uid=10481 #1
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "smsto"
D/VoicemailCleanupService( 4311): Cleaning up data for package: com.test.thalitest
W/GeofencerStateMachine( 1205): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "mms"
I/Launcher( 1291): Deferring update until onResume
I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "mmsto"
I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "sms"
I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2158): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "mms"
I/PackageManager(  993): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  993):   Action: "android.intent.action.SENDTO"
I/PackageManager(  993):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  993):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450228284
I/ActivityManager(  993): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4577 uid=10059 gids={50059, 3003, 1028, 1015}
I/InternalIcingCorporaPro( 2158): UpdateCorporaTask done [took 79 ms] updated apps [took 79 ms] 
D/dalvikvm(  993): GC_EXPLICIT freed 971K, 65% free 18038K/50296K, paused 5ms+12ms, total 154ms
D/AndroidRuntime( 4545): Shutting down VM
D/dalvikvm( 4545): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
W/ActiveOrDefaultContextProvider( 4577): Missing scope.enter somewhere. Returning default context
I/ActivityManager(  993): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4599 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager(  993): Killing 4021:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/GAV2    ( 4577): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 4599): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 4349): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4349): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4349): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1387): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1387): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1387): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1387): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1387): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1355): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1355): Shutting down VM
D/ChimeraCfgMgr( 1387): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1387): Module APK com.google.android.play.games already loaded
W/dalvikvm( 1355): threadid=1: thread exiting with uncaught exception (group=0x416e1d40)
E/SQLiteLog( 1387): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1387): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 1387): threadid=51: thread exiting with uncaught exception (group=0x416e1d40)
E/DriveAsyncService( 1387): disk I/O error (code 3850)
E/DriveAsyncService( 1387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1387): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1387): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1387): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1387): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1387): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1387): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1387): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1387): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1387): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1387): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1387): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1387): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1387): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 1387): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/dalvikvm( 1387): Jit: resizing JitTable from 4096 to 8192
E/AndroidRuntime( 1355): FATAL EXCEPTION: main
E/AndroidRuntime( 1355): Process: com.google.process.gapps, PID: 1355
E/AndroidRuntime( 1355): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 1355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1355): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 1355): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1355): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1355): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 1355): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 1355): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1355): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1355): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1355): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1355): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1355): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1355): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 1355): 	... 10 more
E/SQLiteDatabase( 1387): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1387): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1387): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 1387): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1387): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1387): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1387): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1387): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1387): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1387): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1387): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1387): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 1387): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
